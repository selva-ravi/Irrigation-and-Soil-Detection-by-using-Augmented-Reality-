# Irrigation-and-Soil-Detection-by-using-Augmented-Reality-
We are monitoring the level of water and moisture content of the soil in the field by using sensor. The sensor give the message to the phone by using GSM module.It is used to control the pumping level without manual operation.IoT, is connected to the internet and integrated into the system to measure the three-dimensional (3D) coordinates of objects. The relationships among accuracy, object coordinates, augmented information (e.g., virtual objects), and object interaction are investigated.
Farm
{
Farm_name;
Farm_description;
list of Farm_Region_Vo;
list of farmer;
}
Farm_Region
{
Region_id;
Region_description;
AR
{
(x,y,z);
(h,w,d);
}
IOT
{
List of sensor;
}
List of farm_iot_vo;
INFO;
}
Plant
{
Plant_id;
Plant_description;
AR
{
(x,y,z)
Current_region_id_lot_id;
}
IOT
{
Tag;
}
INFO;
}
Farmer
{
Farmer_id;
Farmer_description;
AR
{
(x,y,z)
Current_region_id_lot_id;
List (region_id_iot_id_time)
}
IOT
{
Tag;
}
INFO;
}
sensor
{
sensor_id;
sensor_description;
AR
{
(x,y,z)
}
IOT
{
Type;
}
INFO;
}
Farm_lot_vo 
{
lot_id;
lot_description;
AR
{
(x,y,z);
(h,w,d);
}
IOT
{
Type of sensor;
List of Plant;
}
INFO;
}




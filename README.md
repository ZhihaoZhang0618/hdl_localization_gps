# hdl_localization_gps
add heading and fix messages on the base of
\<a href="https://github.com/koide3/hdl_localization">hdl_localization</a>

Good performance with GNSS RTK.


## Load
- ***/utm_file*** 
  - lat lon high heading(ENU) when start mapping

## Sub
My addition:
- ***/fix*** (sensor_msgs::NavSatFixConstPtr)
  -  lat lon high 
  -  I didn't use high, it didn't stable.
- ***/heading*** (geometry_msgs::QuaternionStamped)
  - heading(NEU)

## Other 

geographic-dev need to be installed

sudo apt-get install libgeographic-dev


## Related packages

- [interactive_slam](https://github.com/koide3/interactive_slam)

- <a href="https://github.com/koide3/hdl_graph_slam">hdl_graph_slam</a>
- <a href="https://github.com/koide3/hdl_localization">hdl_localization</a>
- <a href="https://github.com/koide3/hdl_global_localization">hdl_global_localization</a>
- <a href="https://github.com/koide3/hdl_people_tracking">hdl_people_tracking</a>





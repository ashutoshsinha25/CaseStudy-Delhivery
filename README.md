# Delhivery :

Delhivery is the largest and fastest-growing fully integrated player in India by revenue in Fiscal 2021. They aim to build the operating system for commerce, through a combination of world-class infrastructure, logistics operations of the highest quality, and cutting-edge engineering and technology capabilities. The Data team builds intelligence and capabilities using this data that helps them to widen the gap between the quality, efficiency, and profitability of their business versus their competitors.

The company wants to understand and process the data coming out of data engineering pipelines:
  • Clean, sanitize and manipulate data to get useful features out of raw fields
  • Make sense out of the raw data and help the data science team to build forecasting models on it


# Column Profiling :
- data - tells whether the data is testing or training data
- trip_creation_time – Timestamp of trip creation
- route_schedule_uuid – Unique Id for a particular route schedule
- route_type – Transportation type
- FTL – Full Truck Load: FTL shipments get to the destination sooner, as the truck is making no other pickups or drop-offs along the way
- Carting: Handling system consisting of small vehicles (carts)
- trip_uuid - Unique ID given to a particular trip (A trip may include different source and destination centers)
- source_center - Source ID of trip origin
- source_name - Source Name of trip origin
- destination_cente – Destination ID
- destination_name – Destination Name
- od_start_time – Trip start time
- od_end_time – Trip end time
- start_scan_to_end_scan – Time taken to deliver from source to destination
- is_cutoff – Unknown field
- cutoff_factor – Unknown field
- cutoff_timestamp – Unknown field
- actual_distance_to_destination – Distance in Kms between source and destination warehouse
- actual_time – Actual time taken to complete the delivery (Cumulative)
- osrm_time – An open-source routing engine time calculator which computes the shortest path between points in a given map (Includes usual traffic, distance through major and - minor roads) and gives the time (Cumulative)
- osrm_distance – An open-source routing engine which computes the shortest path between points in a given map (Includes usual traffic, distance through major and minor roads) (Cumulative)
- factor – Unknown field
- segment_actual_time – This is a segment time. Time taken by the subset of the package delivery
- segment_osrm_time – This is the OSRM segment time. Time taken by the subset of the package delivery
- segment_osrm_distance – This is the OSRM distance. Distance covered by subset of the package delivery
- segment_factor – Unknown field


# Business Recommendations : 

1. **Optimize OSRM Trip Planning System**:
   - Enhance the OSRM trip planning system to address discrepancies for transporters, ensuring optimal routing configurations.

2. **Improve Delivery Time Prediction**:
   - Reduce differences between osrm_time and actual_time to enhance delivery time prediction accuracy and provide customers with more reliable delivery estimates.

3. **Ensure Consistency in Distance Calculation**:
   - Investigate and resolve discrepancies between osrm distance and osrm segment distance covered to address potential causes such as route deviations or inaccuracies in route prediction.

4. **Enhance Service in Key States**:
   - Focus on improving service penetration in high-demand states like Maharashtra, Karnataka, Haryana, by optimizing existing corridors and expanding coverage.

5. **Customer Profiling for Key States**:
   - Conduct customer profiling for states with high order volumes (Maharashtra, Karnataka, Haryana, and Tamil Nadu) to understand buying patterns and enhance overall customer experience.

6. **Strategic Planning Based on State Conditions**:
   - Utilize insights into traffic congestion and terrain conditions in different states to strategize and meet demand effectively, especially during peak festival seasons.

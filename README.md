# Final-Project-Tableau

<img width="240" alt="Just a lil plane" src="https://github.com/user-attachments/assets/7c475a0b-2e40-4d75-b1b6-1e926366bb37">

## Project/Goals

Wildlife Strikes represent a very serious risk to pilots and passengers of aircraft. Using historical data from the FAA, a dashboard was created to allow pilots to have a better understanding of the potential strike risks during their upcoming flight.

## Process
### Data Exploration
The data set was fortunately very clean and prepared which allowed me to jump right into the fun part. After reviewing the the data types present in the data set, a simple visualization was created to indetify any high risk times for wildlife strikes:

<img width="480" alt="Strikes by Flight Stage" src="https://github.com/user-attachments/assets/c309ab4c-1e5b-4c98-86e6-595850776871">

As seen above, the highest risk moments are times when the aircraft is on the run way, or during takoff/landing. This is further proven when looking at the breakdown of strikes by distance from the ground:

<img width="480" alt="Strikes by Altitude" src="https://github.com/user-attachments/assets/46814ac1-aece-4de3-8086-2b100a152069">

Further exploration was done to determine the animals that were most involved in the wildlife strike events. As initially thought, birds are far and away the most frequent animal category involved in strikes:

<img width="620" alt="Strikes by Animal Category" src="https://github.com/user-attachments/assets/a5b7d021-0c1a-4c64-9b76-aedb1c27a3f0">



### Dashboard Creation
With some trends already discovered, a dashboard was created to allow pilots to look at the strike risk for their upcoming flight:

<img width="960" alt="Screenshot 2024-10-28 at 12 04 32 PM" src="https://github.com/user-attachments/assets/50307e72-a93c-43e6-8b7f-fca217a75dcb">

This dashboard can be filtered by Airport, State, Month, Hour of the day, and Phase of the Flight providing an interactive way for pilots to get a sense of the risk level for strikes at their takeoff and landing times/locations.

By clicking the bird, pilots will be directed to the BirstCase Live Migration Map. As birds are most prevelant in strikes, this map allows pilots to see if there are any large migration events occuring near their take of and landing locations.

## Results
Option 2 was chosen for this project and I wanted to indentify if their were any high-risk times of the year for wildlife strikes to occur. This lead me down the path of discovering high-risk locations, times of day, and phases of flight. With that information and the corresponding visualiztions ready, I decided to create a dashboard to be used by pilots. Wildlife strikes can be very dangerous events, and it is important for pilots to have all of the information they can to reduce the risk of these events occuring. In this case, providing pilots with information may help them make more informed decisions regarding take-off and landing, or even just keep a better eye out for potential dangers.


## Future Goals
Moving forward I would like to gather information on successful flights as well. This could help create some better risk assesments. As of this time the dataset only contains flights where a strike did occur. That makes it difficult to determine if certain times are truly at higher risk of wildlife strikes, or if those are just busier times for flights.

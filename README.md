java cEESA01Introduction to Environmental ScienceLaboratory ManualFall 2024Lab 2: Weather and Climate Data
IntroductionIn lectures, we will soon begin discussing the Earth’s energy balance, the basics of climate, and other atmospheric phenomena. This lab will begin discussing these concepts, by introducing students to the instruments that are used to collect weather data, how weather data is used to describe climate, and how this type of data is analyzed.The main learning objectives of this lab are:1) to become familiar with different types of instrumentation used in environmental science, specifically for describing weather (meteorology);2) to see the instruments used to collect weather data, and3) to learn how to manipulate, analyze, and make calculations with large datasets using spreadsheet (Microsoft Excel) software.Weather Variables in BriefWeather refers specifically to the conditions of the atmosphere at any particular time and place. Weather is constantly changing and is comprised of multiple different variables that describe multiple complementary aspects of atmospheric conditions. In this lab we will use data collected at UTSC, to evaluate and summarize weather according to the following variables:
1. Precipitation
2. Wind speed and direction
3. Atmospheric or barometric pressure
4. Air temperature
5. Radiative or energy fluxes (e.g., insolation, incoming solar radiation)
6. Humidity
Some of these are quite intuitive, but we provide a brief recap here to ensure everyone is on the same page.
Precipitation is either liquid or solid water particles falling from clouds to the Earth’s surface by the force of gravity as rain, snow, or hail. These are measured in mm of precipitation over a given amount of time (mm per day, mm per month, mm per year). Commonly, rainfall precipitation is measured using rain gauges (Figure 1); this is the type of data we will use for this lab. Quantifying snowfall precipitation is just as critical for understanding our environment and is evaluated by a variety of techniques including snow gauges. Though today we will not deal with snow.Wind is the horizontal bulk movement of air across the Earth’s surface. Wind is quantified in terms of their prevailing direction (i.e., the cardinal direction from which they are blowing (Figure 7)), as well as their strength (measured in km per hour). Weathervanes are used to measure wind direction, whereas anemometers are used to measure wind speed. Often these two instruments are combined into one instrument called a vane anemometer that can measure both wind direction and speed simultaneously (Figure 2).Atmospheric or barometric pressure is a measure of the downward pressure exerted by the weight of the air in Earth’s atmosphere. Alternatively, it is the amount of force exerted over an area of surface by the air above. Very generally, low pressure weather systems are those that “attract” wind, force it upwards, and ultimately result in precipitation. Barometric pressure is measured in kilopascals (kPa). The instrument used to measure atmospheric pressure is the barometer (Figure 3).Temperature is rather obvious, but more technically, it is a measure of sensible energy, or the energy that we can feel. Temperature is measured in units of degrees Celsius (° C). Unless you are in the United States; they still use Fahrenheit. Thermometers and a variety of electronic sensors, such as thermocouples and thermistors, are used to measure temperature (Figure 4).Incoming solar radiation (“insolation”) represents the energy flux striking the Earth’s surface from the Sun at a given place and time. Since this is a measure of energy, it is measured in units of energy over a given area (specifically, kilojoules per m2). Insolation can be measured using an instrument called a pyranometer (Figure 5). Recall in Lab 1, that we needed to calculate the amount of energy needed to grow all of the grasses and seeds for the prey for our owl. We could, technically, measure this directly using a pyranometer.
Humidity is slightly more complicated. While it can generally be defined as the amount of water vapour in the air, in actuality, there are three main measurements of humidity: A) relative humidity, B) absolute humidity, and C) specific humidity. However, in everyday life and for our purposes in this lab, relative humidity is the most often reported and experienced.Relative humidity refers to the ratio of the amount of water vapour that is present in the air, to the maximum amount of water vapour required for saturation at that particular temperature and pressure. In other words, relative humidity describes how close the air is to being saturated with water vapour. By extension, relative humidity is measured as a percentage, and can be measured using multiple instruments including hygrometers, sling psychrometers, and electronic probes (Figure 6).While relative humidity is a meteorological measurement, we actually most commonly see this reported as “the Humidex”: a way of reporting how air actually feels when you step outside. This is slightly different and is calculated following a three-step process (which we will do in this lab).First, relative humidity can be used in conjunction with temperature, to approximate the dew point: the atmospheric temperature at which a particular air mass will be saturated (i.e., 100% relative humidity) with respect to water vapour. 代 写EESA01 Lab 2: Weather and Climate Data Fall 2024
代做程序编程语言This can be calculated using the following steps/ formulae. First, we calculate:
Tdew = Tair – [(100 - RH) / 5] Equation 1Where:Tdew 	is the dew point in degrees Celsius (° C)Tair 	is air temperature in degrees Celsius (°C)RH 	is relative humidity in %.Second, if one knows the dew point, we can then calculate the actual vapour pressure (e) of the air mass as:
Equation 2Where:e 	is the vapour pressure in millibars (mb)Tdew 	is the dew point in degrees Celsius (°C).Third, once you have information on vapour pressure, it is relatively easy to calculate the Humidex with the following formula:Equation 3
Where:
Tair 		is the air temperature in °C
e 		is the vapour pressure in millibars (mb)
0.5555 	is a factor that corrects for the use of the metric system (and not the Fahrenheit scale).Figure 1. A rain gauge used for collecting precipitation data.Figure 2. A vane anemometer used to collect wind speed and direction data.Figure 3. A brass barometer for collecting atmospheric pressure.Figure 4. A mercuric weather thermometer.Figure 5. A pyranometer for measuring incoming solar radiation (or insolation).Figure 6. Weather instruments that measure humidity.Figure 7. Cardinal directions.DirectionDegreesN315-360, 0-45E45-135S135-225W225-315Procedure for Laboratory 2
Step 1. Familiarize yourself with Microsoft Excel, or a similar spreadsheet program, like Numbers for Mac. Your teaching assistants will teach you the basics of using spreadsheets during this lab.
Step 2. Download the two data files from UTSC’s weather station, which are available on Quercus under the “EESA01 2024 Practicals/ Lab Information” Module.
These files present daily weather data for the months of June and July, and are titled “EESA01 2024 Lab 2 June 2024 data.xlsx”, and “EESA01 2024 Lab 2 July 2024 data.xlsx”, respectively. Both present the following meteorological variables for a given month:
Average temperature in ° C (AirTC_AVG)
Relative humidity in % saturation (RH)
Barometric Pressure in kPa (BP_kPa_AVG)
Total rainfall precipitation in mm (Rain_mm_TOT)
Average windspeed in kilometers per hour (WS_kph_AVG)
Wind direction in degrees (°)
Average solar irradiance in watts per m2 (SlrW_AVG)
Total solar irradiance in kilojoules per m2 (SlrkJ_2_TOT)
Step 3. Open this file and familiarize yourself with the content. Prior to leaving the lab for Step 4 below, ensure you have seen this dataset, know where to locate it, and have confirmed all of these columns.
Tip: This is the key data source for Lab 2 so take the time to review it carefully while you are here.

Step 4. Field trip time! In your groups, travel to the weather station and see what instruments measure certain meteorological variables.

Tip: We are going on an environmental excursion, visiting the UTSC weather station. Dress appropriately. Although it is not snowing or raining now, who knows?Laboratory 2 AssignmentAssignment 1 is 45 marks total and is worth 15% of your final grade.
Please submit a PDF version of your assignment on Quercus under “Lab 2 submission”. Your lab 2 assignment is due before the beginning of Lab 3 (so please consult Quercus for the individualized deadlines).Question 1. Using the weather data from the UTSC weather station (Step 2), A) calculate average monthly values for June and July separately, for all weather variables where the average is appropriate. Then B) calculate total monthly values for June and July separately, for any weather variables where a summed value is appropriate. Use the appropriate Excel functions.When submitting this question, submit two tables, one for June and one for July, that clearly shows the sums or average values for each month. Make sure these values are clearly labeled (9 marks).Question 2. Use Equation 1 above to calculate the dew point for every day in both June and July. Use this information to calculate the mean dewpoint for each month.Next, use Equation 2 above to calculate the vapour pressure for every day in both June and July. From there, use Equation 3 above to calculate the humidex for every day in both June and July. Finally, calculate the mean humidex for each month.In submitting your responses, kindly organize your answers in a neat, clearly labeled table (10 marks).Question 3. Using IF/THEN statements, change the daily average wind direction to quadrants entitled “N”, “S”, “E”, and “W”, such that:for “N”, use >315-45 °for “S”, use >135-225 °for “E”, use >45-135 °for “W”, use >225-315 °Calculate the dominant wind direction for each month by calculating the “mode”. In your submitted answer, include the formulae (i.e., the IF/THEN statements) you used to calculate each wind direction (10 marks).Question 4. Make a scatterplot that shows the relationship between daily temperature and daily solar irradiance. Be mindful of which variables should be on the independent and dependent axes. Add a linear trendline to the data and include both an equation and r2 value for the trendline.Comment on the observed relationship in terms of its strength, and why you would or would not expect a strong statistical relationship (10 marks).Question 5. In less than 10 lines, explain how a vane anemometer works. You will have to do some research and reference your sources using APA style. What two meteorological variables does this instrument measure (6 marks)?

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

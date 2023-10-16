# Electricity_Demand_Management

This project, developed by Pirate-Emperor, focuses on managing electricity demand during peak periods using machine learning (ML) models for forecasting and optimization.

## Abstract
- India is the world’s third largest energy consuming country whose need for the energy increases rapidly from 106.6 billion units(BU) in 2019 to 124.2 BU in 2021 to 132 BU in 2022.Majority of which is met by coal reserves in several states, that are running out fast causing Power Blackouts.India loses about $86 billion annually to power sector distortions and Blackouts as per World Bank."The power outages across the country due to coal shortage are due to the lack of coordination amongst the coal ministry, railway ministry and power ministry. Every ministry claims that they are not responsible for the present mess in the power sector," AIPEF said in a statement.

-	We aspire to resolve this issue by flattening and matching the demand to supply curve of energy.We wish to Achieve this result to reduce the probability of power grid failure which are the main cause of power outage affecting metro, hospitals and Disrupt communications.In order to accomplish this result we must study the behavioral pattern of both industrial as well as domestic consumption which constitute of 41.09% and 25.67% of the total power consumption using DTW/K-means (to form clusters and label the result) and LLM model to suggest methods to save electricity during production while keeping in mind the Key variables such as weather patterns,geographical location and Transmission Constraints etc.Enhanced and Accurate Forecasting that incorporate weather data, historical patterns, and machine learning algorithms for Flexible Generation Scheduling to complement and balance the variable output of renewable energy sources to maintain grid stability to help the Independent system operators (ISOs) along side Users to keep a track of their activities.We intend to suggest measures such as variable pricing to tackle the Uncertainty throughout the year due to weather conditions, or special events.this shall be done by expanding the scope of application of smart meters currently in use.
	
-	Many large scale industries are already started to adapt allowing us to shift our focus to domestic and small to medium scaled businesses.We expect to face the challenges such as Domestic Household Datasets are lacking the appliances specific metering.Weather patterns which affect both the usage and generation of energy from renewable sources making it more complex.Variable and Uncertain Generation due to  unexpected outages or require maintenance, reducing the overall available generation capacity.The electricity grid requires a constant balance between supply and demand to maintain stable operating conditions.Sudden Fluctuations in generation or demand can impact the grid's stability, leading to issues like frequency deviations.We need to be predict such fluctuations and preare reserves to compensate for the fluctuations.
 
## Features

- **Load Forecasting**: Uses historical electricity consumption data to predict future load using ML models.
- **Demand Response**: Implements demand response strategies to shift or shed load during peak times.
- **Optimization**: Applies optimization techniques to reduce peak demand and distribute loads evenly.
- **Cost Savings**: Offers solutions to minimize electricity costs during peak hours.
- **User-friendly Interface**: Provides an intuitive dashboard for easy monitoring and decision-making.

## Description

Topic Name: Demand Response Solutions for Peak Load Management

The Objective of this project is to satisfy electricity demands of every region of India 24/7. This project is achieving this by incorporating the principle of flattening the electricity demand curve as sudden rise/fall in electricity demand leads to machine failure and wastage of electricity to change the grid supply to such fluctuations, and which further leads to power outages. Solution to the above problem is by changing the user's behaviour to balance the electricity needs. When the electricity demand is constant then the chance of grid failure and wastage of wattage during meeting the fluctuations in electricity demand will be negligible and hence power outages will be drastically reduced. The following points explain the underlying feature of this project:
1) Aim to prevent Power Outages (Flattening the Demand Curve).
2) To reduce the probability of grid failures (Flattening the Demand Curve).
3) Why this model? -> Domestic Household Datasets are lacking the appliances specific metering.
4) Why flattens the curve?
   - Renewables Resources (Solar Panel during Rainy Season can't be used and those users’ electricity demands will be dependent on government provided power stations and hence there will be sudden rise in electricity demand during rainy season)
			  - Power Outages
			  - Grid Failure (Equipment Disrupts due to sudden rise and fall in demand)
6) Industrial Sector (Large Scale) already has well-organised electricity management/ their own power stations so the chances of saving electricity are minimal and these organizations have steady electricity demand.
6 Target: 
	i) Domestic:
		* Use of DTW/K-means (to form clusters and label the result) and DTW/KNN to (to predict cluster from previous labels)
		- Suggest practices to flatten the demand curve:
			- Alerts: To warn the consumer to reduce their consumption during those time period
			- Energy Storage Integration
			- Variable Pricing (Low for Low Demand) as per similar clusters within an electricity region (defined by a cluster of similar labels in geographical area)
			- Forecasting and Adaption: To predict the power consumption of the consumers (region wise) and suggest changes before a day or two prior to it.
			- Flexible Generation Scheduling: Use of flexible generation resources to meet the demands to compensate for the fluctuations
			- Contribution to Nature (Reduction in Carbon Footprints)
	ii) Small Scale Industry 
		- Use of LLM model to suggest methods to save electricity during production
7 Challenges:
	i) Variable Demand: Uncertainty in weather, holidays, varying household needs.
	ii) Variable Generation: Power outages, Maintenance and rise of Renewable resources
 	iii) Grid Stability: Sudden Fluctuations in electricity demand will impact the grid's stability
	iv) Integration of Renewable Energy: Variability in (during Rainy Season) usage would have bad impact on the electricity demand curve 
	v) Need for Appliances-specific Readings.

## Prerequisites

To run the project, you will need:

- Python 3.x
- Required Python libraries (numpy, pandas, scikit-learn, matplotlib, etc.)

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/Pirate-Emperor/Electricity_Demand_Management.git
cd Electricity_Demand_Management
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Usage

Run the main Python script:

```bash
python main.py
```

The script will use historical electricity consumption data to train the ML models and predict future load. It will also apply demand response strategies and optimization techniques to manage electricity demand during peak hours.

## Data Source

The project requires historical electricity consumption data with time-series information, such as date, time, and electricity consumption. You can obtain the data from public datasets or your local utility provider.

## Development

To enhance the project, you can modify the Python scripts in the `src` directory. Some potential areas for improvement include:

- Exploring more sophisticated ML models for load forecasting.
- Enhancing the demand response strategies for better load management.
- Integrating weather forecasts and other external factors for improved predictions.
- Improving the user experience of the dashboard.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

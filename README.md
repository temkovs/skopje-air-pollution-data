# Air pollution data: A dataset gathered through a crowd sensing platform

## Authors:
- Slave Temkov
- Pance Cavkovski
- Petre Lameski
- Eftim Zdravevski
- Michael A. Herzog
- Vladimir Trajkovik

## Keywords:
- air pollution
- crowdsourcing
- time series analysis
- predictive analytics

## Project:
Cleanbreathe project (https://cleanbreathe.eu/)

## Abstract:
This is a dataset on air pollution monitoring sourced from a crowd-sensing IoT platform. The dataset includes real-time data on various pollutants, including PM2.5, PM10, and NO2 levels, along with atmospheric data such as humidity and temperature. This data is collected across multiple urban locations in Skopje, North Macedonia.

## Description:
The dataset is provided as is, without any preprocessing involved. Additional data is also available through the pulse.eco API. The data is structured in 2 CSV files. The first file contains the actual data - measures for a certain pollutant or atmospheric type of data from an identified sensor at a specific time point. Each row in this file represents one measurments, containing 4 columns: • SensorId - a unique identifier (string) of the sensor where the measure- ment came from • Type - the type of the measurement (pm10, pm25, co, humidity and so on) • Value - the value that was measured • Stamp - the timestamp of when exactly was the measurement recorded The second file is where the metadata for the sensors is stored. This contains of 6 columns: • SensorId - a unique identifier (string) of the sensor • Type - the type ID of the sensor • Position - geographical coordinates of where the sensor is placed (lati- tude, longitude) • Description - short description or name of the sensor • Comments - additional comments regarding the sensor • Status - the status of the sensor

# 🌍 Earthquake Data Analyzer

This is a Python project built as part of the **Code in Place** final project. It analyzes global earthquake data to uncover patterns in magnitude, frequency, depth, geography, and time.

## 📊 Demo Video
Watch the YouTube demo for a walkthrough of the project:
👉 [Demo Video](https://www.youtube.com/watch?v=_rQDH7ZQ18Y)

## 📂 Dataset Source

While the project uses a simplified `.csv` file for demonstration, the data originally comes from the [IRIS Interactive Earthquake Browser (IEB)](https://ds.iris.edu/ieb/), which allows users to explore and export global seismic data.

## 🧾 Sample Dataset Format

Year,Month,Day,Time,Lat,Lon,Depth,Mag,Region,Timestamp
2011,03,11,05:46:24,38.297,142.373,29,9.1,"2011 Great Tohoku Earthquake, Japan",1299822384
2004,12,26,00:58:53,3.295,95.982,30,9.1,"2004 Sumatra - Andaman Islands Earthquake",1104022733

## 🛠 Features

The Earthquake Data Analyzer provides insights such as:

✅ Total and yearly number of earthquakes

✅ Magnitude statistics (average, max, thresholds)

✅ Depth distribution and extremes

✅ Geographical clustering

✅ Monthly trends and historical magnitude trends

✅ Highlighting significant seismic events (e.g., M ≥ 8.0)

## 🧪 Example Output

Data loaded successfully.
First few records:
   Year  Month  Day      Time     Lat      Lon  Depth  Mag   Region                       Timestamp
0  2011      3   11  05:46:24  38.297  142.373   29.0  9.1   2011 Great Tohoku Earthquake 1299822384

Statistical summary of the data:

Frequency Analysis:
Total number of earthquakes: 2500
Number of earthquakes per year:
 1970    58
 1971    58
 ...
Number of earthquakes per decade:
 1970    374
 1980    401
 ...

Magnitude Analysis:
Average Magnitude: 6.86
Maximum Magnitude: 9.1
Number of earthquakes with magnitude >= 8.0: 43
...

## 🧑‍💻 How to Run

1. Clone the repository:
'''bash
git clone https://github.com/ichsanhibatullah/earthquake-data-analyzer.git
cd earthquake-data-analyzer
2. Make sure you have Python 3 and pandas installed:
'''bash
pip install pandas
3. Run the analyzer:
'''bash
python earthquake_analyzer.py

## 📁 Files
- earthquake_analyzer.py — main analysis script
- earthquake_data_largest.csv — input dataset
- README.md — this file

## 📈 Future Improvements
- Add data visualization (e.g., using matplotlib or Plotly)
- Create an interactive web app
- Fetch real-time data directly from seismic APIs

## 🤝 Acknowledgments
- Thanks to Code in Place for the opportunity.
- Data from [IRIS Earthquake Browser](https://ds.iris.edu/ieb/).
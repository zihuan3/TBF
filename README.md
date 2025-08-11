**Mount Pinatubo Climate Impact Analysis**

**Overview**

This project analyzes the global climate impact of Mount Pinatubo's 1991 volcanic eruption through data visualization. Using NASA temperature data, I explored how one of the 20th century's largest volcanic eruptions affected global temperatures and demonstrated the significant cooling effect that volcanic aerosols can have on Earth's climate system.

**Features**

- Time series visualization of global temperature anomalies from 1985-1995
- Comparison between raw monthly data and 12-month running mean
- Analysis of temperature patterns before, during, and after the eruption
- Clear visualization of volcanic cooling effects despite concurrent climate factors

**How to Run**

- Open the notebook in Google Colab: https://colab.research.google.com/drive/1rcYXr6gWkGpB3pu4YYw59abWycCQ87mp

    **Option 2: (Cells didn't run automatically)**
    - Download NASA GISTEMP dataset: https://data.giss.nasa.gov/gistemp/tabledata_v4/GLB.Ts+dSST.csv
    - Run all cells and upload NASA GISTEMP dataset in order to reproduce the analysis
    - All necessary data processing and visualization will be generated automatically

**Technologies Used**

- Python
- Pandas (data manipulation and analysis)
- Matplotlib (data visualization and plotting)
- NumPy (numerical operations)

**Dataset**

- NASA GISTEMP: https://data.giss.nasa.gov/gistemp/tabledata_v4/GLB.Ts+dSST.txt
- NASA GISS: https://data.giss.nasa.gov/modelforce/strataer/tau.line_2012.12.txt
- Volcanic Eruption Ref.: https://earthobservatory.nasa.gov/features/Volcano
- Content: Global temperature anomalies in Celsius
- Time Period: 1985-1995 (focusing on the decade surrounding the eruption)
- Preprocessing: Calculated 12-month running mean for trend analysis

**Key Findings**

- Mount Pinatubo's eruption caused a measurable global cooling effect
- The volcanic impact is clearly visible even when accounting for other concurrent natural climate factors
- The 12-month running mean effectively highlights the sustained cooling trend following the eruption
- Other natural disasters occurring during this period would have typically caused opposite temperature effects, making Pinatubo's cooling impact even more significant

**Future Improvements**

- Compare with other major volcanic eruptions (e.g., Tambora 1815, Krakatoa 1883)
- Incorporate additional climate variables (precipitation, atmospheric pressure)
- Analyze regional temperature variations rather than just global averages
- Add statistical significance testing for the observed temperature changes

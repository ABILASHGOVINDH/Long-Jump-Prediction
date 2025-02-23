# Long Jump Performance Prediction 🏃‍♂️📊

This project predicts and visualizes the long jump performance of an athlete from ages 12 to 16 using historical data. It uses **linear regression** to project future performance and compares it to the **state record**. The project is implemented in a Jupyter Notebook and includes visualizations and analysis.

---

## 📂 **Project Structure**
- **Folder Path**: `C:/Users/avina/OneDrive/Desktop/git hub/long_jump_prediction`
- **File Path**: `C:/Users/avina/OneDrive/Desktop/git hub/long_jump_prediction/long jump predicting.ipynb`
- **GitHub Repository**: [Long-Jump-Prediction](https://github.com/ABILASHGOVINDH/Long-Jump-Prediction)

---

## 🛠️ **How It Works**
1. **Data Input**:
   - Historical data for long jump performance at ages 10 and 11 is provided.
   - Example:
     ```
     Age (Years): [10, 11]
     Planned (m): [3.5, 4.8]
     Actual (m): [2.4, 2.8]
     ```

2. **Linear Regression**:
   - A linear regression model is created using `numpy.polyfit` to predict future performance.
   - The slope and intercept of the regression line are calculated.

3. **Projection**:
   - The model projects performance from ages 12 to 16 (monthly and yearly).
   - Random noise is added to simulate realistic variations in performance.

4. **Visualization**:
   - A graph is plotted to compare:
     - Historical data (purple dots).
     - Actual performance (green line).
     - Planned performance (blue dashed line).
     - State record (horizontal line at 8.72 meters).

5. **State Record Check**:
   - The script checks if the projected performance can beat the state record (8.72 meters).
   - Output: `She can beat the state record! 🎉`

---

## 📈 **Key Features**
- **Historical Data Analysis**: Uses past performance to predict future results.
- **Monthly and Yearly Projections**: Provides detailed projections for each month and year.
- **Visualization**: Clear graphs to compare actual vs. planned performance.
- **State Record Comparison**: Checks if the athlete can beat the state record.

---

## 🚀 **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/ABILASHGOVINDH/Long-Jump-Prediction.git


## 📊 Sample Output
Graph:

Historical data (purple dots).

Actual performance (green line).

Planned performance (blue dashed line).

State record (horizontal line at 8.72 meters).

## Projected Data:
Age (Years)  State_Record  Actual_Distance  Planned_Distances
12.0         8.72          3.25             3.20
13.0         8.72          3.70             3.60
14.0         8.72          4.20             4.00
15.0         8.72          4.65             4.40
16.0         8.72          5.10             4.80

## State Record Check:
She can beat the state record! 🎉

### 🛠️ Dependencies
Python 3.x

Libraries:

numpy

pandas

matplotlib

## Install dependencies using:
 pip install numpy pandas matplotlib

## 📝 Contributing
# Feel free to contribute to this project! 🚀

Fork the repository.

Create a new branch: git checkout -b feature-name.

Commit your changes: git commit -m "Add feature".

Push to the branch: git push origin feature-name.

Open a pull request.

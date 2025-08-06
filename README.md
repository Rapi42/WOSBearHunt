# ⚔️ Whiteout Survival - Formation Calculator

A powerful web-based tool to help players optimize their troop formations in Whiteout Survival. Calculate the optimal distribution of Infantry, Lancers, and Marksmen across your marches and rally for maximum combat effectiveness.

## 🎯 Features

- **Smart Troop Allocation**: Automatically distributes troops based on damage priority (Marksmen > Lancers > Infantry)
- **Flexible Configuration**: Support for 4-6 marches with customizable deployment limits
- **Minimum Requirements**: Set minimum troop amounts for each unit type
- **Real-time Calculation**: Instant results with detailed breakdowns
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **Visual Feedback**: Color-coded troop types with clear results display

## 🎮 How It Works

### Troop Types
- **Infantry** (🟢) - Poor damage, used for minimum requirements
- **Lancers** (🟡) - Good damage, secondary priority
- **Marksmen** (🔴) - Best damage, highest priority

### Allocation Algorithm
1. **Minimum Allocation**: Distributes minimum required troops to each march and rally
2. **Marksmen Distribution**: Allocates remaining Marksmen equally across all units
3. **Lancer Distribution**: Distributes remaining Lancers if space allows
4. **Infantry Distribution**: Fills remaining space with Infantry

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic understanding of Whiteout Survival troop mechanics

### Setup Instructions

1. **Access the Calculator**
   - Visit: `https://rapi42.github.io/WOSBearHunt`
   - No installation required - works directly in your browser

2. **Enter Your Troop Counts**
   - Input your total Infantry, Lancers, and Marksmen
   - Set your number of marches (4-6)
   - Configure deployment limits for marches and rally

3. **Set Minimum Requirements**
   - Define minimum troop amounts for each type
   - These will be allocated to every march and rally

4. **Calculate and Deploy**
   - Click "Calculate Optimal Formation"
   - Review the results and deploy accordingly

## 📊 Input Parameters

### Troop Counts
- **Infantry**: Total number of Infantry troops available
- **Lancers**: Total number of Lancer troops available  
- **Marksmen**: Total number of Marksman troops available

### Deployment Settings
- **Number of Marches**: Between 4-6 marches
- **Deployment Limit per March**: Maximum troops per march (e.g., 60,000)
- **Rally Deployment Capacity**: Maximum troops for your rally

### Minimum Requirements
- **Min Infantry per Unit**: Minimum Infantry for each march/rally
- **Min Lancers per Unit**: Minimum Lancers for each march/rally
- **Min Marksmen per Unit**: Minimum Marksmen for each march/rally

## 📈 Results Display

### Squad Formation
Shows total troops allocated across all marches:
- Infantry distribution
- Lancer distribution  
- Marksman distribution

### Rally Formation
Shows troops allocated to your personal rally:
- Infantry allocation
- Lancer allocation
- Marksman allocation

### Summary Statistics
- **Total Troops Used**: Sum of all deployed troops
- **Total Leftover**: Remaining troops after allocation
- **Squad Total**: Total troops across all marches
- **Rally Total**: Total troops in rally

## 🎨 Customization

The calculator is designed to be flexible and can be customized for:
- Different troop ratios
- Various deployment limits
- Custom minimum requirements
- Different march configurations

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs or issues
- Suggest new features
- Submit improvements to the algorithm
- Enhance the user interface

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on GitHub
- Check the input validation messages
- Ensure all values are within valid ranges

## 🎯 Game Strategy Tips

- **Prioritize Marksmen**: They deal the most damage
- **Maintain Minimums**: Having some of each troop type is often beneficial
- **Balance Your Marches**: Distribute troops evenly for consistent performance
- **Monitor Leftovers**: Use leftover troops for additional marches or training

---

**Happy Hunting! ⚔️**

*This tool is designed to help optimize your Whiteout Survival formations. Results are based on the allocation algorithm and should be used as a guide for your strategic decisions.*

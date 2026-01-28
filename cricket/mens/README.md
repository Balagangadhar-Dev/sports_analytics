# Men's Cricket Analytics

Comprehensive statistics and analysis for men's cricket across international matches, domestic leagues, and various cricket formats.

## 📁 Folder Structure

```
mens/
├── README.md              # This file
├── [data_category_1]/     # Specific data category (e.g., international, domestic, etc.)
├── [data_category_2]/
└── ...
```

## 📊 Data Categories

Data is organized by cricket format and competition:

### International Cricket

- **Test Matches** - Five-day international test cricket
- **ODI (One Day International)** - 50-over international matches
- **T20I (Twenty20 International)** - 20-over international matches

### Domestic Leagues

- **IPL** - Indian Premier League
- **Big Bash** - Australian domestic T20 league
- **County Cricket** - English domestic cricket
- **Other Domestic Leagues** - Regional and national domestic competitions

### Player Data

- Career statistics and records
- Performance metrics (batting averages, bowling figures, strike rates, etc.)
- Historical milestones and achievements
- Season-by-season progression

## 📝 Contents

### Data Files

Raw data files stored in CSV, JSON, or other formats:
- Player information and biographical data
- Match scorecards and detailed records
- Batting and bowling statistics
- Team compositions and lineups
- Performance in different formats and conditions
- Career highlights and records

**Current Files:**
- `mens_cricket_stats.csv` - Main cricket statistics file (add description here based on actual contents)

### Analysis Notebooks

Jupyter notebooks for data exploration and analysis:
- Exploratory Data Analysis (EDA)
- Player performance rankings
- Format-specific analysis (Test vs ODI vs T20)
- Career trajectory analysis
- Performance comparisons between eras
- Statistical predictions and modeling

## 🔧 How to Add Data

1. Create a new subfolder with a descriptive name (e.g., `international_2024`, `ipl_2024`)
2. Add your raw data files
3. Create analysis notebooks as needed
4. Add a README.md in the subfolder documenting:
   - Competition/format name
   - Data source and collection methodology
   - Data schema and field descriptions
   - Time period covered
   - Available notebooks and their purpose

## 📋 Data Guidelines

- **Naming Convention**: Use snake_case for file names (e.g., `ipl_2024_player_stats.csv`)
- **Formats**: Prefer CSV for tabular data, JSON for complex nested structures
- **Metadata**: Include cricket format, competition, season, data source, and collection date
- **Documentation**: Document any data transformations, cleaning steps, or calculations

## 📈 Common Metrics

### Batting Metrics
- Runs scored, innings played, average, strike rate
- Centuries, half-centuries, not outs
- Highest score, dismissal types

### Bowling Metrics
- Wickets taken, overs bowled, runs conceded
- Bowling average, economy rate, strike rate
- Best bowling figures, maiden overs

### Fielding Metrics
- Catches, run-outs, stumpings
- Fielding position preferences
- Participation in key moments

## 🤝 Contributing

When adding men's cricket data or analysis:

1. Determine the appropriate category (international format, domestic league, etc.)
2. Ensure data is properly validated and cleaned
3. Document the cricket format and competition clearly
4. Include comprehensive metadata about the data source
5. Add analysis notebooks with clear comments and explanations
6. Update this README if adding new data categories
7. Reference data sources and collection methodology

## 📚 Cricket Format Reference

- **Test Cricket**: Longest format, up to 5 days per match, 90 overs per day
- **ODI (One Day International)**: 50 overs per side, typically completed in one day
- **T20I (Twenty20 International)**: 20 overs per side, fastest international format
- **T20 (Domestic)**: Domestic twenty-over format
- **List A**: Four-day domestic or regional cricket

## 🔗 External Resources

Add links to cricket databases, statistical websites, and reference materials as the repository develops.

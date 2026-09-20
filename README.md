# 🏠 Austin Housing Data Insights — Power BI Business Analysis

## 📌 Project Overview

This project analyses **15,171 residential properties** across the Austin, Texas housing market using **Power BI**.

The purpose of the project is to investigate how residential property prices vary according to:

- Geographic location
- Property type
- Property size
- Property features
- School characteristics
- Housing amenities
- Property configuration

The Power BI report was designed as an **interactive business analysis tool**, allowing users to move from a high-level market overview into detailed geographic, school, and property-feature analysis.

The project demonstrates the complete analytical process from raw housing data through data modelling, DAX calculations, interactive filtering, visual analysis, and business insight generation.

---

# 🎯 Business Problem

The Austin residential property market contains substantial variation in housing prices, property characteristics, neighbourhoods, and surrounding amenities.

For property buyers, investors, real-estate professionals, and market analysts, headline property price alone does not explain these differences.

The business therefore requires an analytical solution capable of answering:

- Where are higher- and lower-priced properties concentrated?
- Which property types dominate the market?
- How do property characteristics differ across price segments?
- Are school characteristics associated with differences in property value?
- Which property features are commonly associated with higher median prices?
- Which variables appear to influence listing price?
- How can users dynamically explore different property segments?

---

# 🎯 Project Objectives

The objectives of this project are to:

1. Provide an executive overview of the Austin housing market.
2. Analyse the distribution of properties across different home types.
3. Compare average and median housing prices.
4. Identify geographic concentrations of residential properties and price levels.
5. Analyse school characteristics across Austin neighbourhoods.
6. Investigate how property features correspond with median listing prices.
7. Identify variables associated with higher listing prices.
8. Allow users to dynamically filter and segment the housing market.
9. Translate visual analysis into business-oriented insights.

---

# 📊 Dataset Overview

| Metric | Result |
|---|---:|
| Total Properties | **15,171** |
| Median Property Price | **$405,000** |
| Average Property Price | **$512,768** |
| Median Living Area | **1,975 sq ft** |
| Average Living Area | **2.21K sq ft** |
| Median Lot Size | **8,276 sq ft** |
| Average Lot Size | **119K sq ft** |
| Maximum Living Area | **109K sq ft** |
| Maximum Property Price | **$13.5M** |

The dataset contains information relating to:

- Property price
- Home type
- ZIP code
- City
- Street address
- Latitude and longitude
- Living area
- Lot size
- Bedrooms
- Bathrooms
- Garage spaces
- Parking features
- Number of stories
- Year built
- Cooling
- Heating
- Spa
- View
- Homeowners association
- Appliances
- School rating
- School size
- Classroom size
- Nearby school types

---

# 🛠 Tools & Techniques

- **Power BI Desktop**
- **Power Query**
- **DAX Measures**
- **Data Modelling**
- **Field Parameters**
- **Dynamic Visuals**
- **Slicers and Interactive Filters**
- **Geographic Mapping**
- **Key Influencers**
- **Conditional Analysis**
- **Business Intelligence**
- **Business Analysis**
- **Data Visualisation**

---

# 📑 Dashboard Structure

The Power BI report is organised into four main analytical areas:

1. **Summary**
2. **Location**
3. **Schools**
4. **Property Features**

A dedicated filter panel allows users to refine the analysis across multiple property and neighbourhood dimensions.

---

# 🔎 1. Summary Dashboard

The Summary page provides the executive-level view of the Austin residential property market.

### Core KPIs

- **15,171 properties**
- **$405K median property price**
- **$512.8K average property price**
- **1,975 sq ft median living area**
- **8,276 sq ft median lot size**

The page also analyses:

- Property count by home type
- Property count by ZIP code
- Properties by year built
- Median vs average home price by property type
- Availability of major property features

---

## 🏡 Housing Type Distribution

Single-family properties dominate the dataset.

| Property Type | Property Count |
|---|---:|
| Single Family | **14,241** |
| Condo | **470** |
| Townhouse | **174** |
| Multiple Occupancy | **96** |
| Vacant Land | **83** |

Approximately **94% of the dataset consists of Single Family properties**.

### Business Interpretation

The dataset predominantly represents the Austin single-family housing market.

Insights derived from the report should therefore be interpreted primarily within this market rather than as an equally weighted representation of every residential property type.

---

# 💰 Median vs Average Property Price

The dashboard compares median and average property prices across property types.

Overall:

- **Median Property Price:** ~$405K
- **Average Property Price:** ~$513K

The average is substantially higher than the median.

### Business Interpretation

The Austin property-price distribution is positively skewed.

A relatively small number of expensive properties increase the average price above the value of a typical property.

For affordability and representative market analysis, **median price is therefore generally more informative than average price**.

---

# 🗺️ 2. Location Analysis

The Location page provides an interactive geographic view of properties throughout the Austin area.

Users can select a home-price range and observe where properties within that range are geographically concentrated.

The map uses:

- Latitude
- Longitude
- Average property price

The page can also be refined using the report's filter panel.

### Business Purpose

The Location analysis allows users to identify:

- Geographic concentrations of properties
- Premium property areas
- Lower-price residential areas
- Spatial differences within the Austin housing market
- Property clusters corresponding with selected price ranges

### Business Interpretation

The Austin housing market is not geographically uniform.

Property values differ substantially between locations, meaning geographic segmentation should be considered when comparing properties or assessing market opportunities.

---

# 🎓 3. School Analysis

The Schools page investigates neighbourhood education characteristics and their relationship with the housing market.

### School KPIs

| Metric | Result |
|---|---:|
| Average School Rating | **5.85** |
| Average School Size | **1.24K students** |
| Median Students per Teacher | **14.8** |
| Average Primary Schools | **0.91** |
| Average Middle Schools | **1.08** |
| Average High Schools | **0.94** |
| Average High School Size | **1.335K students** |

The page includes:

- Geographic distribution of school-rating groups
- Property count by ZIP code
- School rating categories
- School size analysis
- Students-per-teacher analysis

---

## School Rating Segmentation

Properties are segmented into school-rating categories such as:

- Poor
- Average
- Good
- Exceptional

The 100% stacked visual allows users to examine how property populations within different ZIP codes are distributed across these categories.

### Business Interpretation

School characteristics vary considerably across Austin neighbourhoods.

Higher-rated school areas are also associated with higher property-value segments within the dataset.

However, this relationship should be interpreted as **association rather than causation**, since neighbourhood location, household income, property size, land value, and other factors may contribute simultaneously.

---

# 🔥 4. Property Features Analysis

The Features page investigates how median property price changes across different property characteristics.

A dynamic field parameter allows users to switch the analysis between different property attributes.

Examples include:

- Garage spaces
- Bedrooms
- Bathrooms
- Parking features
- Number of parking features
- Number of stories
- Appliances
- Home type

The page also provides feature-level filters for:

- Homeowners association
- Cooling
- Heating
- Spa
- View

---

# 📊 Median Price by Property Attribute

The central chart dynamically calculates **Median Home Price** against the selected property characteristic.

This allows users to investigate questions such as:

- How does median price change with additional garage spaces?
- Do properties with more bathrooms occupy higher-value market segments?
- Does property type influence median price?
- Are larger or more feature-rich homes concentrated in higher price ranges?

### Business Purpose

Rather than creating a separate chart for every property characteristic, the dynamic parameter allows multiple business questions to be investigated through a single interactive visual.

---

# 🧠 Key Influencers Analysis

The dashboard includes Power BI's **Key Influencers** visual to investigate variables associated with increases in Listing Price.

Variables analysed include:

- Living area
- Lot size
- Bedrooms
- Bathrooms
- Garage spaces
- Parking
- Stories
- Appliances
- Property features
- Year built

### Business Interpretation

Listing price is not driven by one isolated property characteristic.

The analysis indicates that property value should instead be evaluated as the result of multiple interacting dimensions including:

**Location + Property Size + Property Configuration + Amenities + Neighbourhood Characteristics**

---

# 🏊 Feature Availability and Median Price

The dashboard directly compares median property prices based on whether selected features are available.

Examples include:

| Feature | Without Feature | With Feature |
|---|---:|---:|
| Garage | ~$385K | **~$425K** |
| Spa | ~$399K | **~$575K** |
| View | ~$395K | **~$475K** |

### Business Interpretation

Properties containing premium features such as spas, views, and garages tend to occupy higher-price segments.

However, these figures should **not** be interpreted as the direct monetary value added by the feature.

For example:

> A $176K median-price difference between properties with and without spas does not mean that installing a spa increases a property's value by $176K.

Properties containing these features may also differ in location, size, land area, construction quality, and overall market segment.

---

# 🔍 Dynamic Filter Panel

A major component of the report is the interactive filter panel.

Users can filter the dashboard using:

### Property Configuration

- Number of bedrooms
- Number of bathrooms
- Garage spaces
- Parking features
- Number of parking features
- Number of stories
- Appliances

### Property Features

- HOA
- Cooling
- Heating
- Spa
- View
- Home type

### Location

- City
- ZIP code
- Street address

### School Characteristics

- School rating
- School size
- Classroom size

### Numeric Range Filters

- Listing price
- Living area
- Year built
- Lot size

### Business Value

This allows users to perform self-service analysis and investigate specific housing segments without requiring separate reports.

For example, a user could isolate:

> 3-bedroom properties with garages, strong school ratings, specific ZIP codes, selected price ranges, and recent construction years.

The dashboard can therefore support multiple stakeholder questions through a single analytical interface.

---

# 💡 Key Business Insights

## 1. Austin Housing Prices Are Highly Segmented

The large difference between median and average price demonstrates the presence of a significant premium-property segment.

---

## 2. Single-Family Housing Dominates the Market

Approximately 94% of analysed properties are Single Family homes.

The dataset therefore provides particularly strong insight into this market segment.

---

## 3. Location Is a Critical Analytical Dimension

Geographic mapping shows that property-price levels are concentrated differently across Austin.

Austin should therefore not be analysed as a single homogeneous housing market.

---

## 4. Property Size Is Strongly Associated With Price

Living area, lot size, bedrooms, and bathrooms all provide important information when evaluating residential property prices.

---

## 5. School Environment Is Associated With Housing Segmentation

School rating and other education characteristics vary significantly across ZIP codes and correspond with different residential market segments.

---

## 6. Premium Features Are Associated With Higher Median Prices

Properties with:

- Garages
- Spas
- Views

generally show higher median prices than properties without these features.

---

## 7. Property Value Is Multi-Dimensional

No single variable fully explains residential property price.

A meaningful valuation assessment should consider multiple dimensions simultaneously.

---

# 💼 Business Recommendations

## 1. Use Median Price as the Primary Market Benchmark

Because premium properties materially increase the average, median price provides a more representative measure of typical property value.

---

## 2. Compare Properties Within Similar Locations

Property comparisons should be performed within relevant ZIP codes or geographic areas rather than across Austin as a whole.

---

## 3. Compare Similar Property Types

Single-family homes, condominiums, townhouses, and other property types should not automatically be benchmarked against one another.

---

## 4. Use Multiple Property Characteristics During Valuation

Property assessment should incorporate:

- Location
- Living area
- Lot size
- Bedrooms
- Bathrooms
- Property type
- Year built
- School characteristics
- Amenities

---

## 5. Treat Feature Premiums Carefully

Higher median prices for properties with garages, spas, or views indicate market association rather than direct causal value.

These characteristics should be considered together with broader property quality and location.

---

## 6. Use Interactive Segmentation for Stakeholder Analysis

The report's filter panel allows stakeholders to create highly specific housing segments.

This can support:

- Buyer property searches
- Investor screening
- Market comparisons
- Neighbourhood analysis
- Property positioning
- Real-estate market research

---

# ⚠️ Analytical Limitations

## Dataset Composition

Approximately 94% of properties are Single Family homes, meaning other housing types have much smaller sample sizes.

---

## Association Does Not Equal Causation

Relationships between property price and variables such as:

- School rating
- Garage availability
- Spa
- View
- Living area

represent observed associations.

The analysis does not establish that these variables independently cause property-price changes.

---

## Confounding Variables

Location, land value, property size, neighbourhood characteristics, and amenities may influence property prices simultaneously.

---

## Extreme Property Values

The dataset contains very high-value and unusually large properties.

These outliers can significantly influence averages.

Median measures are therefore used throughout the report where appropriate.

---

# 📌 Executive Conclusion

The Austin housing market demonstrates substantial variation across geography, property structure, neighbourhood characteristics, and available amenities.

The typical property in the dataset has a median price of approximately **$405K**, while the substantially higher average of approximately **$513K** indicates the influence of premium properties.

Single-family housing represents approximately **94% of analysed properties**, making it the dominant residential segment.

Geographic location, living area, lot size, property configuration, school characteristics, and selected amenities all show meaningful relationships with residential property value.

The analysis therefore demonstrates that housing valuation should be approached as a **multi-dimensional business problem** rather than relying on property price alone.

The Power BI solution provides users with an interactive environment for moving from an executive market overview into detailed location, school, and property-feature analysis.

---

# 📸 Dashboard Preview

## Summary Dashboard

![Summary Dashboard](images/summary-dashboard.png)

The Summary page provides an executive overview of property count, median price, property size, housing type, construction year, geographic distribution, and major property features.

---

## Location Analysis

![Location Analysis](images/location-analysis.png)

The Location page allows users to select property-price ranges and identify their geographic concentration across Austin.

---

## School Analysis

![School Analysis](images/school-analysis.png)

The School page analyses school rating, school size, student-teacher ratios, geographic school-rating patterns, and property distribution by ZIP code.

---

## Property Features Analysis

![Property Features](images/features-analysis.png)

The Features page uses dynamic parameters, Key Influencers, price segmentation, feature comparison, and interactive filtering to analyse variables associated with residential property prices.

---

# 📂 Repository Structure

Austin-Housing-Data-Insights/
│
├── README.md
│
├── data/
│   └── austinHousingData.xlsx
│
├── powerbi/
│   └── housing_data_project.pbix
│
├── images/
│   ├── summary-dashboard.png
│   ├── location-analysis.png
│   ├── school-analysis.png
│   ├── features-analysis.png
│   └── filter-panel.png
│
└── presentation/
    └── Austin_Housing_Business_Analysis.pdf

---

# 🧠 Skills Demonstrated

- Business Problem Definition
- Business Requirements Analysis
- Data Cleaning
- Data Transformation
- Power Query
- Data Modelling
- DAX Measures
- KPI Development
- Field Parameters
- Dynamic Visualisation
- Geographic Analysis
- Market Segmentation
- Key Influencers Analysis
- Interactive Filtering
- Business Insight Generation
- Data Visualisation
- Power BI Dashboard Development
- Business Storytelling
- Analytical Documentation

---

# 👤 Author

**Odysseus**

Business Analyst / Data Analyst Portfolio Project

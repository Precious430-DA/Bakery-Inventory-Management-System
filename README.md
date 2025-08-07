# Bakery Inventory Management System

## Overview
A comprehensive inventory tracking system developed during my role as Operations Manager at a commercial bakery. This system provides real-time inventory monitoring, usage analytics, and automated restocking alerts to ensure optimal production continuity.

## Key Features

### 📊 **Real-Time Inventory Tracking**
- Current stock levels for all raw materials and packaging
- Multi-unit support (PCS, KG, GRMS)
- Pack size tracking for procurement planning

### 📈 **Usage Analytics** 
- Daily usage rate calculation based on 5-day rolling average
- Predictive inventory planning with "Days Remaining" forecasting
- Historical consumption pattern analysis

### ⚠️ **Automated Alert System**
- **RESTOCK SOON**: Triggered when current stock < 50% of daily usage
- **ADEQUATE STOCK**: Sufficient inventory levels maintained
- Proactive restocking to prevent production disruptions

## System Metrics

| Metric | Description | Business Impact |
|--------|-------------|-----------------|
| **Usage Rate** | Average daily consumption over 5-day period | Enables accurate demand forecasting |
| **Days Remaining** | Current Stock ÷ Daily Usage Rate | Prevents stockouts and production delays |
| **Restock Threshold** | 50% of daily usage rate | Maintains safety stock levels |

## Sample Data Insights

### Critical Items (Requiring Immediate Attention)
- **VEG OIL**: 0.54 days remaining ⚠️
- **EGG**: 3.50 days remaining ⚠️
- **IMPROVER**: Out of stock (0 days) 🚨

### Well-Stocked Items
- **SALT**: 44.97 days remaining
- **RESINS**: 32.60 days remaining
- **MILK**: 32.60 days remaining

## Technical Implementation

### Data Structure
```
Item Name | Qty in Stock | Unit | Pack Size | Usage Rate (Per Day) | Days Remaining | Actionable Insights
```

### Logic Framework
- **Restock Algorithm**: `IF (Current Stock < Daily Usage × 0.5) THEN "RESTOCK SOON"`
- **Days Calculation**: `Days Remaining = Current Stock ÷ Daily Usage Rate`
- **Usage Tracking**: 5-day rolling average for demand smoothing

## Business Impact

### ✅ **Achievements**
- **Zero Production Delays**: Proactive restocking prevented stockouts
- **Optimized Cash Flow**: Reduced excess inventory by 25%
- **Improved Efficiency**: Automated monitoring saved 2+ hours daily
- **Cost Reduction**: Eliminated emergency purchases at premium prices

### 📋 **Operational Benefits**
- Real-time visibility into inventory status
- Data-driven procurement decisions
- Standardized restocking procedures
- Reduced manual tracking errors

## Skills Demonstrated

- **Operations Management**: End-to-end inventory optimization
- **Data Analysis**: Usage pattern recognition and forecasting
- **Process Automation**: Automated alert systems
- **Cost Management**: Inventory turnover optimization
- **Excel/Spreadsheet Mastery**: Advanced formulas and conditional logic

## Future Enhancements

- [ ] Integration with POS systems for real-time usage updates
- [ ] Supplier lead time incorporation
- [ ] Seasonal demand adjustment algorithms
- [ ] Mobile dashboard for remote monitoring
- [ ] Automated purchase order generation

## Context
Developed and implemented during tenure as Operations Manager at HoneyBee Bakery, managing inventory for daily production. System handled 15+ SKUs with varying consumption patterns and procurement cycles.

---

*This project showcases practical application of data analytics and operations management in a fast-paced production environment, demonstrating ability to create actionable business intelligence from operational data.*

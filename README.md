# User Journey Optimization : Reducing Drop Offs & Boosting Conversions and Retentions for B2C Product

## 🎯 Problem Statement

Modern B2C businesses face critical challenges in understanding customer behavior and optimizing conversion funnels. Key problems addressed in this analysis:

1. **High abandonment rates**: 68% of users abandon carts without purchasing
2. **Conversion inefficiencies**: Only 2.1% of sessions convert to sales
3. **Segment unawareness**: Lack of clarity on high-value customer segments
4. **Mobile underperformance**: 15% lower conversion on mobile vs desktop
5. **Pricing uncertainties**: Optimal discount levels and shipping thresholds unknown

This project aims to uncover actionable insights to:
- Reduce funnel drop-offs
- Improve cross-device performance
- Enhance personalization strategies
- Optimize pricing and promotions
- Increase customer retention

## 📊 Key Findings

### 1. Funnel Drop-off Analysis
- **Highest drop-off**: 35% between adding to cart and starting checkout
- **Final conversion**: Only 2.1% of sessions result in completed purchases
- **Critical stages**: 
  - Cart → Checkout: 35% drop-off
  - Payment → Purchase: 26% drop-off

### 2. Device Type Impact
| Metric          | Mobile | Desktop |
|-----------------|--------|---------|
| Conversion Rate | 1.8%   | 2.1%    |
| Session Duration| 8.2 min| 6.5 min |

### 3. Cart Abandonment
- **Overall rate**: 68% abandonment
- **Abandonment points**:
  - Shipping selection: 42%
  - Payment: 31%
  - Cart: 27%

### 4. Payment Method Analysis
| Method          | Conversion | Avg Order Value |
|-----------------|------------|-----------------|
| Credit Card     | 78%        | $112            |
| PayPal          | 72%        | $98             |
| Cash on Delivery| 62%        | $85             |

### 5. Customer Retention
- **Repeat customers**: 18% of all users
- **Avg purchases/user**: 1.3
- **30-day retention**: 24%

### 6. RFM Segmentation
| Segment              | % Users | % Revenue |
|----------------------|---------|-----------|
| Champions            | 12%     | 48%       |
| Loyal Customers      | 18%     | 28%       |
| At Risk              | 15%     | 12%       |
| Hibernating          | 32%     | 5%        |

### 7. Checkout Optimization
- **Page load impact**: Each +1s decreases conversion by 2.3%
- **Step completion**:
  - Checkout start → Shipping: 74%
  - Shipping → Payment: 69%
  - Payment → Purchase: 74%

### 8. Price Sensitivity
| Cluster          | Sensitivity | Avg Order Value |
|------------------|-------------|-----------------|
| Price-sensitive  | High (0.82) | $89             |
| Premium          | Low (0.19)  | $145            |
| Neutral          | Medium      | $112            |

### 9. Discount Impact
| Discount Tier | Conversion Rate |
|---------------|-----------------|
| 0%            | 2.1%            |
| 5%            | 2.8%            |
| 10%           | 3.2%            |
| 15%           | 3.5%            |
| 20%           | 3.1%            |

### 10. Shipping Fee Impact
- **Free shipping**: +32% conversion boost
- **A/B Test Results**:
  - Control: 2.1% conversion
  - Free shipping $50+: 2.6%
  - Free shipping $75+: 2.7%

### 11. Time-Based Patterns
- **Peak activity**: 8 PM (15% of daily sessions)
- **Best conversion**: 4-6 AM (4.2% conversion rate)
- **Weekly pattern**: Weekends see 22% more conversions than weekdays

### 12. Product Category Analysis
| Category              | Popularity | Conversion |
|-----------------------|------------|------------|
| electronics.smartphone| 28%        | 3.1%       |
| electronics.laptop    | 22%        | 2.8%       |
| home.kitchen          | 15%        | 3.8%       |
| clothing.womens       | 12%        | 3.2%       |

## 📌 Recommendations

1. **Optimize mobile experience** to close the 15% conversion gap with desktop
2. **Implement exit-intent offers** at key abandonment points (especially shipping)
3. **Promote credit card payments** with incentives to boost AOV
4. **Personalize discounts** (10-15% range performs best)
5. **Test free shipping thresholds** ($75+ showed best results)
6. **Target Champions segment** with loyalty programs (48% of revenue)
7. **Improve page load speed** (each 1s improvement → +2.3% conversion)


## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

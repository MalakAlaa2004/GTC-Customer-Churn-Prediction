# Customer Churn Prediction Web Application

## Phase 4: Deployment via Web Interface

### Phase Authors
- **Mazen Mohammed**
- **Faris Emad**

### Live Application
**Deployed Application**: [https://gtc-customer-churn-prediction-mccg8cqph2e5df95dkx6gb.streamlit.app/](https://gtc-customer-churn-prediction-mccg8cqph2e5df95dkx6gb.streamlit.app/)

### Project Overview
This repository contains the final phase of our customer churn prediction project - a deployed web application that allows business users to interact with our trained machine learning model through an intuitive interface. The application provides instant churn risk predictions based on customer attributes.

### Application Features

#### Core Functionality
- **Interactive Web Interface**: Built with Streamlit for ease of use
- **Real-time Predictions**: Instant churn probability calculations
- **Comprehensive Input Validation**: Ensures data quality and prevents errors
- **Professional Dashboard**: Clean, organized layout with visual feedback
- **Risk Assessment**: Color-coded predictions with actionable recommendations

#### User Experience
- **Guided Input Process**: Step-by-step customer data collection
- **Visual Analytics**: Probability gauge charts and feature importance displays
- **Business Insights**: Risk factor analysis and recommended actions
- **Responsive Design**: Works across desktop and mobile devices

### Technical Architecture

#### Technology Stack
- **Frontend Framework**: Streamlit
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **Visualizations**: Plotly
- **Model Persistence**: Joblib
- **Deployment Platform**: Streamlit Community Cloud

#### Model Integration
The application loads a pre-trained machine learning model (`best_churn_model.pkl`) that processes 19 customer features including:
- Demographics (age, gender, dependents)
- Service usage (phone, internet, streaming)
- Account information (tenure, charges, contract type)
- Payment methods and billing preferences

### Deployment Process

#### Prerequisites
1. Trained machine learning model file (`best_churn_model.pkl`)
2. GitHub repository with project files
3. Streamlit Community Cloud account

#### Deployment Steps

1. **Repository Setup**
   ```
   project-folder/
   ├── app.py                    # Main Streamlit application
   ├── best_churn_model.pkl      # Trained ML model
   ├── requirements.txt          # Python dependencies
   └── README.md                 # Project documentation
   ```

2. **Dependencies Configuration**
   Create `requirements.txt` with necessary packages:
   ```
   streamlit>=1.28.0
   pandas>=2.0.0
   scikit-learn>=1.4.0
   plotly>=5.0.0
   joblib>=1.3.0
   ```

3. **Code Deployment**
   - Upload all files to GitHub repository
   - Ensure repository is public for free deployment
   - Verify model file is within size limits

4. **Streamlit Cloud Deployment**
   - Navigate to [share.streamlit.io](https://share.streamlit.io)
   - Connect GitHub account
   - Select repository and main file (`app.py`)
   - Deploy application

5. **Testing and Validation**
   - Verify all features work correctly
   - Test input validation and error handling
   - Confirm predictions are accurate
   - Check responsive design

### Application Usage

#### For Business Users
1. **Access the Application**: Navigate to the deployed URL
2. **Input Customer Data**: Fill in all required customer attributes using the sidebar form
3. **Generate Prediction**: Click "Analyze Customer Churn Risk" button
4. **Review Results**: 
   - View churn probability percentage
   - Check risk level assessment
   - Read recommended actions
   - Analyze key risk factors

#### Input Categories
- **Demographics**: Gender, senior citizen status, family information
- **Services**: Phone, internet, and additional service subscriptions
- **Account Details**: Contract length, payment method, billing preferences
- **Financial Information**: Monthly charges, total charges, tenure

### Model Performance and Insights

#### Prediction Output
- **Churn Probability**: Percentage likelihood of customer churn
- **Risk Classification**: High, medium, or low risk categorization
- **Visual Dashboard**: Interactive gauge charts and bar graphs
- **Business Recommendations**: Specific actions based on risk level

#### Key Features Analyzed
The model evaluates customer attributes with emphasis on:
- Monthly charges and pricing sensitivity
- Contract type and commitment level
- Service usage patterns
- Payment behavior
- Account tenure and loyalty

### Business Value

#### Immediate Benefits
- **Proactive Retention**: Identify at-risk customers before they churn
- **Resource Optimization**: Focus retention efforts on high-risk segments
- **Decision Support**: Data-driven insights for customer management
- **Cost Reduction**: Prevent revenue loss through early intervention

#### Operational Impact
- **Automated Screening**: Replace manual risk assessment processes
- **Scalable Analysis**: Handle multiple customer evaluations efficiently
- **Consistent Predictions**: Standardized risk evaluation across teams
- **Real-time Insights**: Instant feedback for customer service interactions

### Future Enhancements

#### Potential Improvements
- **Batch Processing**: Upload CSV files for multiple predictions
- **Historical Tracking**: Store and analyze prediction trends
- **Advanced Visualizations**: Additional charts and analytics
- **Model Updates**: Retrain with new data and deploy automatically
- **API Integration**: Connect with existing CRM systems

### Technical Specifications

#### System Requirements
- **Browser Compatibility**: Modern web browsers (Chrome, Firefox, Safari, Edge)
- **Internet Connection**: Required for real-time predictions
- **Device Support**: Desktop, tablet, and mobile responsive

#### Performance Metrics
- **Response Time**: Sub-second prediction generation
- **Uptime**: 99%+ availability through Streamlit Cloud
- **Scalability**: Handles concurrent users efficiently
- **Security**: Input validation and error handling

### Support and Maintenance

#### Troubleshooting
- Verify all input fields are completed before prediction
- Check internet connection for loading issues
- Clear browser cache if application doesn't load properly
- Contact development team for technical issues

#### Updates and Versioning
- Model updates deployed through GitHub repository
- Automatic redeployment when code changes are pushed
- Version control maintains application history
- Regular monitoring ensures optimal performance

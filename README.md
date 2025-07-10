# BG Accounting Software - Serial Number Check

A web-based application designed to fetch and display product serial numbers and expiry dates from Busy accounting software, providing customers with an easy way to check their product warranty and expiration information.

## 🚀 Features

- **Serial Number Lookup**: Quick search functionality for product serial numbers
- **Expiry Date Display**: Clear visualization of product expiration dates
- **Busy Software Integration**: Direct data integration with Busy accounting software
- **User-Friendly Interface**: Intuitive frontend design for easy navigation
- **Real-Time Data**: Live data fetching from the accounting system
- **Responsive Design**: Works seamlessly across desktop and mobile devices

## 📋 Prerequisites

Before running this application, ensure you have the following installed:

- Web browser (Chrome, Firefox, Safari, or Edge)
- Internet connection for data fetching
- Access to Busy accounting software database
- Appropriate permissions to access serial number data

## 🛠️ Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/Lapking-Serial-number-check-.git
cd Lapking-Serial-number-check-
```

### Step 2: Configure Database Connection
1. Update the database configuration file with your Busy software database details
2. Ensure proper credentials are set for database access
3. Test the connection to verify data can be fetched

### Step 3: Deploy the Application
1. Upload files to your web server
2. Configure the web server to serve the application
3. Ensure all dependencies are properly installed

## 📖 Usage

### For Customers
1. **Access the Application**: Open the web application in your browser
2. **Enter Serial Number**: Input your product's serial number in the search field
3. **View Results**: The system will display:
   - Product details
   - Serial number
   - Expiry date
   - Warranty status

### For Administrators
1. **Database Management**: Ensure Busy software database is regularly updated
2. **Monitor Access**: Track application usage and performance
3. **Data Verification**: Regularly verify data accuracy and synchronization

## 🏗️ System Architecture

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Frontend      │    │   Backend API    │    │  Busy Software  │
│   (HTML/CSS/JS) │◄──►│   (Data Layer)   │◄──►│   Database      │
└─────────────────┘    └──────────────────┘    └─────────────────┘
```

## 🔧 Configuration

### Database Settings
- **Host**: Your Busy software database server
- **Port**: Database port (usually 1433 for SQL Server)
- **Database Name**: Your Busy software database name
- **Authentication**: Windows Authentication or SQL Server Authentication

### Application Settings
- **Search Timeout**: Configure search timeout duration
- **Display Format**: Customize date and number formats
- **Language**: Set application language preferences

## 📊 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/search` | GET | Search for serial number |
| `/api/product/{id}` | GET | Get product details |
| `/api/expiry/{serial}` | GET | Get expiry information |

## 🔒 Security Features

- **Input Validation**: All user inputs are validated and sanitized
- **Database Security**: Secure connection to Busy software database
- **Access Control**: Role-based access permissions
- **Data Encryption**: Sensitive data is encrypted in transit

## 🐛 Troubleshooting

### Common Issues

**Issue**: Cannot connect to Busy software database
- **Solution**: Verify database credentials and network connectivity

**Issue**: Serial number not found
- **Solution**: Check if the serial number exists in the Busy software database

**Issue**: Expired dates showing incorrectly
- **Solution**: Verify date format settings and timezone configuration

## 📞 Support

For technical support or questions:
- **Email**: support@yourcompany.com
- **Phone**: +1-XXX-XXX-XXXX
- **Documentation**: [Link to detailed documentation]

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔄 Version History

- **v1.0.0** - Initial release with basic serial number lookup
- **v1.1.0** - Added expiry date visualization
- **v1.2.0** - Improved user interface and mobile responsiveness
- **v2.0.0** - Enhanced Busy software integration

## 🙏 Acknowledgments

- Busy Accounting Software team for database integration support
- Beta testers for valuable feedback
- Development team for continuous improvements

---

**Note**: This application is designed to work specifically with Busy accounting software. Ensure you have proper licensing and permissions to access the required data.
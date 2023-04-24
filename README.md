# Tekium PAN Hunter Script v1.1

It's a tool that can be used to search drives for credit card numbers (PANs). This is useful for checking PCI DSS scope accuracy.

Born from the need to have a tool that is easy to run and use. Being developed in PowerShell doesn't require external libraries. Ideal if you require a tool that searches for possible PAN's in files on Windows computers within your organization.

It's a tool that can be used to search drives for credit card numbers (PANs). 

# Requirements
- Windows computer
- PowerShell (A recent version is recommended)
- PowerShell interface with administrator permissions and with script execution permission

# Execution
Run the following command:

`.\Tekium_PAN_Hunter_Script.ps1 -path_search “C:\Users” -filters ‘*.log’, ‘*.txt’, ‘*.csv’, ‘*.docx’, ‘*.xlsx’`

# Commercial Support
![Tekium](https://github.com/unmanarc/uAuditAnalyzer2/blob/master/art/tekium_slogo.jpeg)

Tekium is a cybersecurity company specialized in red team and blue team activities based in Mexico, it has clients in the financial, telecom and retail sectors.

Tekium is an active sponsor of the project, and provides commercial support in the case you need it.

For integration with other platforms such as the Elastic stack, SIEMs, managed security providers in-house solutions, or for any other requests for extending current functionality that you wish to see included in future versions, please contact us: info at tekium.mx

For more information, go to: https://www.tekium.mx/

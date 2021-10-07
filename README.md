# Azure Proof of Concept

## Download and Install the Azure Storage Explorer Application

Azure Storage Explorer is a free desktop application published by Microsoft.

- Navigate to: https://azure.microsoft.com/en-gb/features/storage-explorer/
- Click 'Download now'
- Save the installer file to your local machine
- Run the installer file

## Connect to Azure Files Storage using Azure Storage Explorer

- Open the Azure Storage Explorer app
- Click on the Connect icon (looks like a plug) in the left side bar
- Select Resource window:
  - Click on the 'Storage account or service' option
- Select Connection Method window:
  - Select 'Connection string (Key or SAS)'
  - Click 'Next'
- Enter Connection Info window:
  - Name: ___NAME_OF_YOUR_CHOICE___
  - Connection string: ___CONNECTION_STRING___
  - Click 'Next'
- Summary window:
  - Click 'Connect'

## Upload a Data Set using Azure Storage Explorer

- Open the Azure Storage Explorer app
- Open the 'Explorer' side window:
  - Click on the 'Explorer' icon (3 dot dash lines) in the side bar
- Navigate to the File Share:
  - Local & Attached > Storage Accounts > ___NAME_SELECTED_ABOVE___ > File Shares > ___FILE_SHARE_NAME___
- Click on the 'Upload' icon in the header
- Select folder or file(s)
- Upload window:
  - Select a folder or file(s) From your local PC to upload
- Click 'Upload'

## Connect to the Azure Virtual Machine using Remote Desktop (Windows)

- Windows Start menu:
  - Type `rdp` > press 'Enter'
- Computer Window:
  - Enter the computer name: ___COMPUTER_NAME___
  - Click 'Connect'
- Credential Window:
  - Click 'More choices'
  - Click 'Use a different account'
  - Enter the Username: ___USER_NAME___
  - Enter the Password: ___PASSWORD___
  - Tick 'Remember me'
  - Click 'OK'
- Certificate Warning Window(s):
  - Click 'OK'


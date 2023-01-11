<p align="center">msw2Pdf is a command-line utility that saves a thread from www.modelshipworld.com into a single PDF file.</p>

## Motivation and Features

- Automate the creation of a single merged PDF from a multiple page thread without opening, printing each page to PDF, and then merging the documents.

## Requirements
Chrome browser

## Usage

- Windows:

  `msw2Pdf-win.exe <url>`

- Mac (OSX)

  Extract the app from the dmg
  Open the msw2Pdf app
  Enter the thread url and press generate 
  To cancel the PDF generation press cancel (Please note this takes a few seconds to cancel) or press exit
  PDFs will be saved in the same folder that the application is run from

### Examples
- Windows:

	`msw2Pdf-win.exe https://modelshipworld.com/topic/22768-18th-century-merchantman-half-hull-planking-kit-by-vthokiee-finished-nrg-148/`

- Mac (OSX):

	Todo: Add images

Note: The current wiondows release requires the format of the url to be h<span>ttps://</span>modelshipworld.com/topic/\<topic\>/ 

## Troubleshooting

	Could not find the Chrome browser

Please verify that Chrome is installed on your computer and is located at one of the following locations
- Windows:
	
	`'C:\Program Files (x86)\Google\Chrome\Application\chrome.exe'`
	
	`'C:\Program Files\Google\Chrome\Application\chrome.exe'`

- Mac (OSX):
	
	`/Applications/Google Chrome.app/Contents/MacOS/Google Chrome`	

## Todo
- [x] Create a user interface instead of utilizing the command line
- [ ] Allow users to enter the location of Chrome if installed in a different directory
- [ ] Allow users to select the save location for threads
- [x] Allow flexibility in the url (i.e. trim content after the number title portion)
- [ ] Provide more error checking on the url

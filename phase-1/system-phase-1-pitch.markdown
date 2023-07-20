# App: Project Name: Phase #1

Date: <MONTH> <DAY>, <YEAR>  
Domain: <DOMAIN_NAME>  
GitHub: https://github.com/codeadamca/<REPO_NAME>  

## Application Purpose

This application will convert a provided image to a set of instructions to recreate the image using LEGO™ bricks. 

The end result will be instructions to create something similar to the LEGO™ World Map (https://www.lego.com/en-us/product/world-map-31203): 

![Sample Map](../images/phase-1-map.png)

## Front-End

Front end facing application will include the following features:

- A place to upload an image, specify width and height, and convert the image to a series of LEGO™ bricks (similar to https://legoimage.com/ or https://mingze-gao.com/apps/legao/)  
- Resulting image can be downloaded as a JPG
- Result will also display a list of required bricks and quantity, should be styled like typical LEGO™ instructions
- Results will also display a copyable matrix of colours
- Instructions can be downloaded as a PDF
- Each submission will be saved to the database

Instructions will look similar to this:

![Sample Instructions](../images/phase-1-instructions.png)

Taken from the World Map LEGO™ instructions:
https://www.lego.com/cdn/product-assets/product.bi.core.pdf/6372756.pdf 
      
## Back-End

Application will include a control panel to achieve the following:

- Login to control panel
- Add, edit, and delete converted images
- View instructions
- Export instructions to PDF

## API

Application API will include the following API calls:

| Method | Endpoint | Description |
| - | - | - |
| POST | /api/convert | Converts a specified image to a matrix of LEGO ™ colours. |
|      |              | Parameters: |

image (required): posted JPG, PNG, or GIF
width (required): number of studs wide
heigh (required)t: number of studs high
format: format to return data in, default is "json"but also accepts "jgp"

Returns:
A matrix of colours for each LEGO ™ brick or a JPG format image. |
# Shopping Cart
This project consists of a shopping cart built with React to run on a local server that communicates with Strapi to populate a catalog of products. Photos for products are randomly populated using lorem picsum images. This project is not compiled, but utilizes the necessary CDNs. All dependencies will need to be installed for production.

## How to Run
This project requires the installation of node v18 or higher and all related dependencies / node modules. An local server is required to run. A Strapi database is required for populating stock.
Substantial portions of code for this project was provided for this student's use pursuant to the completion of MIT xPRO's Professional Certificate in Coding: Fullstack Development with MERN course. All errors are my own.

## Roadmap for Future Improvements
* Address known bugs
* Hide localhost url field at restock button component
* Addition of checkout page
* UI improvements, eg. clearer removal function, replacement of bootstrap accordion format for cart

## Known Bugs
* Query from Strapi db does not add to starting product sheet, adds entries again
* Items added from db cause error - adds duplicate products to cart
* Duplicate items will not change quantity
* Items are not yet returned to stock upon deletion
* Refactor Strapi query

## License
MIT License

Copyright (c) 2020 John Williams

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


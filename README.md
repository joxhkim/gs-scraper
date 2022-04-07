<div id="top"></div>


<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- ABOUT THE PROJECT -->
## About The Project
### Built With

* [Python](https://www.python.org/)


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get started, clone the project to your computer or download it directly as a zip through the repository page.

### Prerequisites

* [Python 3.9+ (make sure to add Python 3.9 to PATH when first installing)](https://www.python.org/downloads/)
* Some sort of text editor is needed, for this project [Visual Studio Code](https://code.visualstudio.com/) is recommended.

### Installation and Running

1. Clone the repository using a command line tool.
    ```sh
    git clone https://github.com/joxhkim/gs-scraper.git
    ```
2. Open the project in your IDE or text editor. Make sure you open the gs-scraper folder to include everything.
    ```sh
    cd C:\Path\To\Project\gs-scraper\
    ```
3. Once you are in the project folder directory, install the required libraries by using:
    ```py
    pip install -r requirements.txt
    ```

5. On the first run create the database by running the create_db() function and removing the scrape() function.
    ```py
    create_db()
    # scrape()
    ```
  
6. After creating the database tables, comment out the create_db() function and uncomment the scrape() function. 
    ```py
    # create_db()
    scrape()
    ```

7. Run the script by using:
    ```py
    py script.py
    ```

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

The purpose of this program is to scrape search results presented on Google Scholar, and then save the scraped results into a local database for use on the REACHUs website. 


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project 
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Email: csjoshkim@gmail.com

<p align="right">(<a href="#top">back to top</a>)</p>



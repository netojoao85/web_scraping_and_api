# Web data extraction techniques (Web scraping & REST APIs) 
<i>From the Theory to the Practice</i>

To better understand Web data extraction techniques, I wrote a literature review based on scientific papers and books about the theme for a higher awareness of steps and decisions to take in practice. Therefore, on this repository, you can find examples of how to automatically gather data from web pages by having the steps and decisions taken under good practices. <br><br>

<b>Keywords:</b> Web scraping, Web crawling, API, Robots.txt, sitemaps,	Regex, HTML DOM, Legal & Ethics, Python, BeautifulSoup, Rvest <br><br>

# Introduction: Extract data from web pages
Webpages are built and designed for human consumption and not for ease and automated data collection (Glez-Peña et al., 2013). For that reason, the data on the websites are unstructured, which implies using tools/methods/techniques to convert them into a structured form (Eswari et. al., 2022). According to Dongo et. al. (2021), three well-known methods have been applied to extract/collect data from web pages:
- Web scraping
- APIs (Application Programming Interface)
- Manual extraction / copy-past method <br>

Web scraping and APIs are automated techniques and the most practical ways to collect data from various website pages and repositories (Dongo et. al. 2021). High speed, accuracy, less labour-intensive and less human errors are advantages of automated techniques compared with manual extraction (Bradley & James, 2019, Dongo et. al. 2021, Eswari et. al., 2022). <br><br>
An API is an interface that allows communication between software, independent of the website structure or content. APIs provide a robust structure to download and interconnect large sets of heterogeneous information (Glez-Peña et al., 2013). Web scraping is gathering data through any means other than a program interacting with an API (Mitchell, 2018). In practice, and due to the different structures of each website (Eswari et. al., 2022), web scraping requires writing software for each one, encompassing a wide range of programming techniques and technologies (Glez-Peña et al., 2013, Mitchell, 2018). <br><br>
Therefore, before scraping a website, it is a good idea to check if it offers an API that allows users to quickly collect data directly from the database behind the website (Bradley & James, 2019). However, whether API does not exist or has limitations, Web scraping to gather the data is needed (Dongo et. al., 2021). 


 

<h2 align='center'>PureSearch</h2>
<h4 align='center'> 👋 Thanks for checking out my project! This is a web application to visualize job board data collected from Indeed.</h4>

---

<h3 align='center'></h3>
</br>
<p>This is the main repo to bridge together my capstone project from App Academy. When I was a recruiter, I had always hoped for a way to automatically aggregate job postings from various markets and funnel them into an interface, so I built one!

This application and web scraper was able to collect more than <b>18 thousand</b> job postings from Indeed.com across seven different geographic markets and four different technologies (Python, JavaScript, Ruby, and Java). After filtering the data through Pandas to wrangle it into something more useful, I was able to extract some really interesting insights into the current US tech market (avg salaries per geographic market, highest salaries per technology, technology with most job volume, etc) This is data that I could have only dreamed of having while recruiting in the competitive NYC tech market.

The project is comprised of several repositories linked here: </p>

<ul>
    <li><a href='https://github.com/ColeRutledge/api'>API</a> - Built with Python and Flask</li>
    <li><a href='https://github.com/ColeRutledge/client'>Client</a> - Built with React</li>
    <li><a href='https://github.com/ColeRutledge/indeed_scraping'>Scraper</a> - Built with Python, Pandas, and Selenium</li>
</ul>

### Takeaways:

<ul>
    <li>Combining Selenium, Pandas, and Beautiful Soup to scrape data that powers interesting and useful applications is very exciting! This project is immediately valuable to me as I enter into my first job search as a developer, and I think that's cool! 😎</li>
    <li>Filtering data in a performant way is tricky.</li>
    <li>I really enjoyed building a small pipeline of data but have a lot of room for improvement and automation. In the months following the bootcamp, I've created a small project that containerizes Selenium and runs Chrome Driver headlessly on my virtual private server with some cron jobs and would like to use it to automate this part of the process. That would be next on the list.</li>
    <li>Pandas is an incredible library! My wife is a financial analyst and used to work in excel all day. Now she uses Python and Pandas <b>every day</b> because of this project. 🚀</li>
    <li>I do love JavaScript, but Python just feels better. ¯\_(ツ)_/¯</li>
</ul>

</br>

---

<p style="margin-top: 5%" align='center'>
    <a href='https://pure-search-client.herokuapp.com/login' target='_blank'>Link to live demo -> Click on Demo User</a><br><i>you may have to give Heroku a minute!<i></br>
</p>

</br>

![PureSearch](pure_search.png)

![PureSearch](pure_search2.png)

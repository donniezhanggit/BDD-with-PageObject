# Add feature file of Selenium-WebDriver sample

Add one feature file "sample.feature" for Selenium-WebDriver sample under "features" folder.

`cd features`

`touch sample.feature`

![alt text](https://raw.githubusercontent.com/hy1984427/BDD-with-PageObject/master/images/CreateSeleniumWebDriverSampleFeature.png "Create Selenium-WebDriver sample.frature")

Edit "sample.feature" to contain following content:

<pre><code>Feature:
In order to check the search result
I want to search on Google and check the browser title

Scenario: Check the browser title after search
    Given I opened Google
    When I search a keyword
    Then I should see the browser title
</pre></code>

![alt text](https://raw.githubusercontent.com/hy1984427/BDD-with-PageObject/master/images/SeleniumWebDriverSampleFeature.png "Edit Selenium-WebDriver sample.frature")

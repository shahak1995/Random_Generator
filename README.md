# Random_Generator
### Description
This is used to Randomly generate API data by calling the api through HTTParty and parsing it into a JSON file to fetch the data into the code. Once this is done,you can test each data block through the use of RSpec when typing in the test methods and running the rspec in the terminal, it says which statements have passed and which havent through green and red; green being that it has passed and red being that it failed.  

### Languages used
* Ruby

### How to download the code
1. Go onto the Github website
2. Type into the search bar this repo: shahak1995/Random_Generator
3. Once you have click the repo you have to click the clone/download button then click Download Zip

### How to use the code
1. Put 'require relative' to the Generator class file at the top

2. In order to create the object for it to be used, you would have to instanciate the generator super class by doing the following:

test = Generator.new

3. After this you have to instanciate the postcodes for example on the generator class into a new variable by doing the following:
 
test.postcodes  

4. Then you can use the methods you want to use from the Generator class by executing it using the following:
 
test.random_array(random_int_value)

5. Doing this example will create an array with postcodes within it with  the random_int_value in which you can put a range of what integers you want to insert to get a range. This is an example below:
 
rand(1..10)

### How to run the Code
1. Run the terminal on the program
2. Type in bundle in the terminal and run it
3. Once this is done it should create a Gemlock file which contains all the dependancies 
4. Once you typed in the test functions within your sprec file you should be able to run RSpec by typing it into the terminal like this 'rspec'
5. It should show all the test statements that have passed and failed through the colours Red and Green; Red being that the test failed and Green being that the test has passed

### Challenges (you can include images and code block here)
1. Testing the different data types within the API
2. Creating the test to check if it passes through RSpec
3. Making sure to call the right methods when making the test
4. To call the API right and parse it through JSON

### Learning points
1. To call the methods correctly when testing 
2. To name the methods correctly
3. To know when to stop testing
4. To name the test methods appropriately to what part in the data you are testing
# How will you add your api request page to frontend?
## **Important!** After making your changes, open a pull request without pushing directly and don't forget to add the front-end team as a reviewer. 
#### 1) First, you need to write your API post and get functions in the "MockAPI.js" file. Below you can find an example of the Post and Get functions.
![image](https://user-images.githubusercontent.com/82322653/236817122-dafd9266-94e3-4b50-b8f3-3b0b559b61f0.png)

#### 2) You need to write your elements correctly in the "apidata.js" file.
* /api/"your_api_page_url_extension" to do that first add an element to apidata dictionary which in apidata.js.
* Your element key must be "your_api_page_url_extension".
* Value of element key is a dictionary which has 2 element. First element is name and must be unique. Second element is form which its value is also a dictionary.
* In form objects value there are 2 elements. First element is buttonText and its value is text on the button. Second element is input and its value is also a dictionary.
* In input objects value, we can add as many input elements as we want to the input object value dictionary from the below input elements.
* On your request page, you can get 2 types of input from the user.

![image](https://user-images.githubusercontent.com/82322653/236806288-36b0754b-3811-430a-bb34-0df1f7c27b13.png)

| Text Input | Select Input |
| --- | --- |
| You can get the input that the user writes in the text section. |You can take the selected option as input by providing options to the user. | 
| Text Input has 3 fields. **type** must be "text", **name** must be a unique name and **label** should be the label name. | Select Input has 4 fields. **type** must be "select", **name** must be a unique name, **label** should be the label name ,and options is an array whose elements are dictionary. Elements have two keys, name and value.  |

#### 3) Check the below example and its output
![image](https://user-images.githubusercontent.com/82322653/236811638-52666c80-9907-412e-b052-9ac802d7eb25.png) 
![image](https://user-images.githubusercontent.com/82322653/236812138-a491e7ce-38b9-4369-88ef-7f2a5b39dee3.png)

## **Important!** After making your changes, open a pull request without pushing directly and don't forget to add the front-end team as a reviewer. 

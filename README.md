# **Web Scraping of TENTE's Online Store**  

## **DESCRIPTION**  
Web scraping of TENTE's online store to extract product data.  

## **TECHNOLOGY EXECUTION**  
Using the **Selenium** library in Python within a Jupyter Notebook, I extracted the **name, price, type of tea/infusion, and ingredients** of each product.  

The script opens a **Chrome** window and executes the entire process automatically, without requiring user interaction. However, I strongly recommend keeping the **Chrome** window active while running the script. Otherwise, the script will **retrieve the tea description instead of the ingredients** (Why? No idea. If you figure it out, let me know!).  

## **OUTPUT**  
The outcome will be a **DataFrame** with all the extracted data. 
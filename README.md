# StarwarsGIF

## **Table of Contents**

1. Project Overview  
2. APIs   
3. Prerequisites  
4. Usage

---

## **Project Overview**

This project fetches a random Star Wars character and shows a gif of it. It displays GIF of famous Star Wars characters without individually searching for them 

Feature: 

* Fetch Star Wars character data   
* Fetch GIF of the character from GIPHY

## **API** 

* [SWAPI](https://swapi.dev/) \- simple star wars database   
* [GIPHY](https://developers.giphy.com/docs/api/endpoint/) \- one of world’s largest GIF library 

### **Prerequisites:**

To run this notebook, you need to set up API for:

1. SWAPI to retrieve a random character

2. GIPHY API (for GIF search)

Navigate to [https://developers.giphy.com/docs/api/endpoint](https://developers.giphy.com/docs/api/endpoint) and register for developers account.

Then you will be provided with a specific key to your api. Copy that and then go to KEY icon on the left side of google colab; add a new secret, name it “GIPHY-KEY”, and put your secret key

## **Usage**

1. Run the notebook cells in order.  
2. The notebook will display up to one random Star Wars character and a gif image related to it.


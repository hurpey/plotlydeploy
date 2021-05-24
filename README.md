Plotly Deploy (Data Visualization in Javascript)

Module 12 Challenge

Overview

The purpose of this analysis is to help Roza finish her partially completed “Belly Button Biodiversity” dashboard. This analysis will enhance the performance of the dashboard and help visualize the bacterial data for each volunteer. Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons after this analysis.  That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.

Results

An interactive webpage, including interactive charts,  was created to visualize and explore the bacterial dataset for each volunteer as shown in Fig 1.7 and Fig 1.8 below.  The link to the webpage is  https://hurpey.github.io/plotlydeploy/

Fig 1.8
<img width="861" alt="Fig 1 8" src="https://user-images.githubusercontent.com/79670933/119284120-f3bfe100-bc0c-11eb-8f31-cb33dbc76dd3.png">


Fig 1.7
<img width="861" alt="Fig 1 7" src="https://user-images.githubusercontent.com/79670933/119284119-f3274a80-bc0c-11eb-93c8-09219ee779f1.png">



Deliverables from the analysis performed are as follows:

1.	A Horizontal Bar Chart showing the top 10 cultures found for each test subject ID number. The result for the Bar Chart is updated as the test subject ID number is changed or updated. For instance, Fig 1.2 and Fig 1.4 below show the results for test subject ID numbers 940 and 943 respectively.

Fig 1.2
<img width="229" alt="Fig 1 2" src="https://user-images.githubusercontent.com/79670933/119283988-962b9480-bc0c-11eb-8540-3887db6d19ef.png">

Fig 1.4
<img width="229" alt="Fig 1 4" src="https://user-images.githubusercontent.com/79670933/119284006-a479b080-bc0c-11eb-992b-b2ccc81c175c.png">


2.	A Bubble Chart showing the bacteria cultures per sample.  The result for the Bubble Chart is updated as the test subject ID number is changed or updated. For instance, Fig 1.3 and Fig 1.6 below show the results for test subject ID numbers 940 and 943 respectively.

Fig 1.3
<img width="570" alt="Fig 1 3" src="https://user-images.githubusercontent.com/79670933/119284041-bc513480-bc0c-11eb-98aa-ef021f3c74c7.png">

Fig 1.6
<img width="570" alt="Fig 1 6" src="https://user-images.githubusercontent.com/79670933/119284040-bc513480-bc0c-11eb-915a-1b5245fd87d0.png">


3.	A Gauge Chart showing the Belly Button Washing Frequency (scrubs per week). The result for the Gauge Chart is updated as the test subject ID number is changed or updated. For instance, Fig 1.1 and Fig 1.5 below show the results for test subject ID numbers 940 and 943 respectively.

Fig 1.1
<img width="229" alt="Fig 1 1" src="https://user-images.githubusercontent.com/79670933/119284088-dd198a00-bc0c-11eb-861f-b7e1028e98a0.png">

Fig 1.5
<img width="229" alt="Fig 1 5" src="https://user-images.githubusercontent.com/79670933/119284087-dc80f380-bc0c-11eb-84be-508e89685862.png">

4. Using HTML and Bootstrap, the webbpage for the dashboard was customized as follows.

body {
    color: #000000;
    background-color: rgb(255, 255, 255);
  }

.tag {
     font-family: inherit; 
     font-size: 1rem;
    }  

.jumbotron {
    background-image: url("../images/bacteria.jpg");
    background-size: 100% 100%;
    text-align: center;
    }

Also, when the dashboard is first opened in a browser, ID 940’s data is displayed in the dashboard, and the three charts working according to their requirements. When a sample is selected, the dashboard displays the data in the panel and all three charts according to their requirements.

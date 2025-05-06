# business-analytics-assignment-3-azure-analytics-for-data-stream-generated-from-atms-solved
**TO GET THIS SOLUTION VISIT:** [Business Analytics Assignment #3-Azure Analytics for data stream generated from ATMs Solved](https://www.ankitcodinghub.com/product/business-analytics-assignment-3-azure-analytics-for-data-stream-generated-from-atms-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96365&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Business Analytics Assignment #3-Azure Analytics for data stream generated from ATMs Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Assignment #3

You are going to use Azure Stream Analytics to process a data stream of ATM transactions and answer stream queries. The schema of the stream is: (ATMCode, CardNumber, Type, Amount)

<ol>
<li>Create a students account at: https://azure.microsoft.com/en-us/free/students/</li>
<li>Setup an Event Hub.</li>
<li>Generate a Security Access Signature (use a terminal with windows operationg system):
https://github.com/sandrinodimattia/RedDog/releases
</li>
<li>Edit Generator.html (open with a text editor, e.g.: Sublime or Notepad++) and update the CONFIG variables. Keep the “js” folder in the same folder as the Generator.html file.</li>
<li>Feed the Event Hub with the use of Generator.html (In order to start the Stream Generator, open the Generator.html with a web browser, e.g.: Chrome and press the “Send Data” button.)</li>
<li>Setup a Storage account.</li>
<li>Upload the Reference Data files to your storage account.</li>
<li>Setup a Stream Analytics Job.</li>
<li>Use the Event Hub + Reference Data Files as Input.</li>
<li>Create a Blob Storage Output.</li>
</ol>
SCENARIO

You have access to a data stream that’s generated from ATMs. Each event contains data related to the transaction that took place. You are asked to create an Azure Analytics solution for the tasks listed in the “QUERIES” section.

REFERENCE DATA

GENERAL NOTES

– Use only the parts of the datasets that you need for the queries. – Use Sublime or Notepad++ to have a proper view of the datasets.

AREA.json

– Geographical Information.

– Connects each area_code with a city and a country.

– The “area_code” of this dataset can be joined with the “area_code” of ATM.json ATM.json

– Information about the ATM.

– Connects each ATM with an area.

– The “atm_code” of this dataset can be joined with the input’s “ATMCode” section. Customer.json

– Information about each customer.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
– Provides demographic information about each customer.

– The “card_number” of this dataset can be joined with the input’s “CardNumber” section.

DATA STREAM INPUT

GENERAL NOTES

Events generated have the following format:

{

“ATMCode”: 13,

“CardNumber”: 5610827137784218, “Type”: 0,

“Amount”: 37

}

FIELDS DESCRIPTION

– ATMCode: Information about the type of the ATM. Can be joined with Atm.json

– CardNumber: The card number related to the transaction. Can be joined with Customer.json – Type: The type of the transaction. There are two types of transactions, type “1” and type “0”. – Amount: The amount of the transaction.

QUERIES

Query 1: Show the total “Amount” of “Type = 0” transactions at “ATM Code = 21” of the last 10 minutes. Repeat as new events keep flowing in (use a sliding window).

Query 2: Show the total “Amount” of “Type = 1” transactions at “ATM Code = 21” of the last hour. Repeat once every hour (use a tumbling window).

Query 3: Show the total “Amount” of “Type = 1” transactions at “ATM Code = 21” of the last hour. Repeat once every 30 minutes (use a hopping window).

Query 4: Show the total “Amount” of “Type = 1” transactions per “ATM Code” of the last one hour (use a sliding window).

Query 5: Show the total “Amount” of “Type = 1” transactions per “Area Code” of the last hour. Repeat once every hour (use a tumbling window).

Query 6: Show the total “Amount” per ATM’s “City” and Customer’s “Gender” of the last hour. Repeat once every hour (use a tumbling window).

Query 7: Alert (Do a simple SELECT “1”) if a Customer has performed two transactions of “Type = 1” in a window of an hour (use a sliding window).

Query 8: Alert (Do a simple SELECT “1”) if the “Area Code” of the ATM of the transaction is not the same as the “Area Code” of the “Card Number” (Customer’s Area Code) – (use a sliding window)

DELIVERABLE

A .pdf file that documents (through screenshots) the process of setting up your account and executing the queries described above. Make sure that you start each job and you include screenshots of the output files.

</div>
</div>
</div>

# eecs3311-lab-1-sorting-hashmap-solved
**TO GET THIS SOLUTION VISIT:** [EECS3311 Lab 1-Sorting HashMap Solved](https://www.ankitcodinghub.com/product/eecs3311-lab-1-sorting-hashmap-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91323&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EECS3311 Lab 1-Sorting HashMap Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2 Problem

</div>
</div>
<div class="layoutArea">
<div class="column">
In this lab, you are expected to tackle the problem of sorting HashMap &lt;K, V&gt; data. HashMap provides default sorting algorithm based on keys (i.e., K), however it does not enable sorting the data based on values (i.e., V). There are many different scenarios that we need to sort data in a HashMap based on its values, e.g., HashMap data structure are widely used to store students’ IDs (keys) and their GPAs (values). When we rank students by their GPAs, we need the value-based HashMap sorting functionality.

There are many different sorting algorithms [1], in this lab, we will adapt two basic sorting algorithms for sorting HashMap based on the values ascendingly, i.e., Bubble Sort1 and Max Heap Sort2. When sorting the values of Maps, we should also move the keys accordingly. You can use two instances of ArrayList to store the values and keys and swap elements in these two ArrayLists synchronously during the sorting tasks.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

•

• •

</div>
<div class="column">
Getting Started

Go to the course eClass page for Section Z. Under Lab 1, download the file EECS3311_Lab1.zip which contains the starter project for this lab.

Unzip the file, and you should see a directory named eecs3311-lab1. It’s a Eclipse project. You can import this project into your Eclipse as an General Java project.

The start project should have the following structure and on default does not compile.

</div>
</div>
<div class="layoutArea">
<div class="column">
•

</div>
</div>
<div class="layoutArea">
<div class="column">
1 https://en.wikipedia.org/wiki/Bubble_sort 2 https://en.wikipedia.org/wiki/Heapsort

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
4 4.1

• • • •

4.2

</div>
<div class="column">
You Tasks

Complete the BubbleSort and HeapSort Classes

You are expected to write valid implementations in the BubbleSort and HeapSort classes. Each instance of “TODO:” in these two classes indicates which implementation you have to complete.

You are expected to implement the specified two sorting algorithms, replace the specified sorting algorithms with other sorting algorithms will receive penalty.

Study the TestBubbleSorting and TestHeapSorting class carefully: it documents how BubbleSort and HeapSort expected to work.

Youmustnotchangeanyofthemethods,parameters,orstatementsintheTestBubbleSortingandTestHeap- Sorting classes.

Write Your Own Test Cases

</div>
</div>
<div class="layoutArea">
<div class="column">
In the StudentTest class, you are required to add as many tests as you judge necessary to test the correctness of BubbleSort and HeapSort.

<ul>
<li>You must add at least 10 test cases in StudentTest, and all of the must pass. (In fact, you should write as many as you think is necessary.)</li>
<li>You will not be assessed by the quality or completeness of your tests (i.e., we will only check that you have at least 10 tests and all of them pass). However, write tests for yourself so that your software will pass all tests that we run to assess your code.</li>
</ul>
</div>
</div>
</div>

# cs3-homework-3-paint-dry-timer-solved
**TO GET THIS SOLUTION VISIT:** [CS3 Homework 3-Paint-Dry Timer Solved](https://www.ankitcodinghub.com/product/cs3-homework-3-paint-dry-timer-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91002&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3 Homework 3-Paint-Dry Timer Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
C++ has several primitive types (int, double, etc) and several core language objects such as string and vector. However, programs often require new objects to achieve elegant designs. One such object may be a TimeCode type, which represents an amount of time in hours, minutes, and seconds.

4:15:32

The above is an instance of a TimeCode object representing 4 hours, 15 minutes, and 32 seconds. An elegant way of implementing this object is to store only one instance variable: t. t is a number representing only the total number of seconds. 4 hours, 15 minutes, and 32 seconds is t = 15,332 seconds.

Your task is to implement a TimeCode object in TimeCode.cpp following this elegant design.

Provided to you is a screenshot of the TimeCode.h file from the solution. It is a screenshot intentionally so that you have to mentally process its contents (by re-typing it). You probably are thinking to yourself, “Oh great! More work! I believe that the minor tedium of re-typing this code will have untold benefits to my academic and professional development for years to come.” and you’re right. It will.

You should implement all of the methods in that file. You may optionally implement more methods (public or private) if it seems appropriate to do so.

In addition to the TimeCode.h screenshot, TimeCodeTests.cpp is provided which contains a small sampling of some of the tests you should perform. When grading this assignment I will use a version of TimeCodeTests.cpp that contains tests for every method of the class. You should significantly expand TimeCodeTests.cpp by coming up with and writing many tests for yourself. Your goal is to test as many cases as you can come up with to ensure that your TimeCode.cpp code can pass all of my tests.

Details

• TimeCodes cannot be negative (for the purposes of this assignment). Their individual components (hour, minute, second) also cannot be negative. Most (all?) of your variables should therefore by unsigned. If a negative value is identified at any point you can throw an exception, which looks like this:

<pre>      throw invalid_argument("Negative arguments not allowed: " + to_string(min));
</pre>
We haven’t learned fully about exceptions yet. You are encouraged to skip ahead to chapter 12 in the ZyBook to explore them further if you’re interested.

</div>
</div>
<div class="layoutArea">
<div class="column">
ZyBook Chapter 7 &amp; Video Lecture 3

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>TimeCodes also cannot have invalid states. For example 00:61:00 should not exist. There are two possible ways to handle this sort of issue depending on the circumstances. I will leave it to you to figure out when to choose them.

◦ 1) Convert the invalid state (0:61:0) to a valid state (01:01:0).

◦ 2) Throw an exception.
</li>
<li>Do not import the math module. Inside TimeCode.cpp the only import is TimeCode.h</li>
<li>The core logic of TimeCode should be GetComponents(), and ComponentsToSeconds(), using these two methods, along with GetTimeCodeAsSeconds() it should be relatively easy to implement all other methods (even the constructors).</li>
<li>Addition and subtraction are intuitive and straightforward conceptually (1:15:22 + 2:9:5 = 3:24:27). They can be confusing when considering roll-over (1:15:55 + 0:1:25). Be careful implementing them!</li>
<li>There is (virtually) no limit on the number of hours.</li>
<li>You should not store hours or minutes or seconds directly. You should only store the total
number of seconds: t.
</li>
<li>Multiplication and division do not make sense between two TimeCode objects (1:0:0 * 0:15:0
= ?). So, they are implemented using a TimeCode and a double (1:0:0 * 0.5 = 0:30:0).

Actually, if you think about it this is always the case for all units of everything. What is 1 apple divided by 1⁄4 of an apple? Is it “4 chunks of apple” ? No, that is nonsense. But, 1 apple divided by 4 is 1⁄4 of an apple.

There is no sample output for this program. You are done when your TimeCode.cpp implements all of the methods in TimeCode.h and passes all of your tests in TimeCodeTests.cpp
</li>
</ul>
</div>
</div>
</div>

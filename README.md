# cs524-homework-5--least-squares-solved
**TO GET THIS SOLUTION VISIT:** [CS524 Homework 5- Least Squares Solved](https://www.ankitcodinghub.com/product/cs524-homework-5-least-squares-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119631&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS524  Homework 5- Least Squares Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
• Submit a single pdf image of your Jupyter notebook via Canvas.

• Please denote the start of each question in your Julia workbook using a LARGEFONT. • Please answer “written” questions in Markdown boxes on your Julia workbook, not by using comments in Code boxes.

• A Julia notebook containing “starter” code for the questions below is supplied.

1. [3 pts] Voltage smoothing. We would like to send a sequence of voltage inputs to the manipulator arm of a robot. The desired signal of target voltages vitarget, i = 1,2,…,200 is shown in the plot below (also available in voltages.csv).

Unfortunately, abrupt changes in voltage cause undue wear and tear on the motors over time, so we would like to create a new signal that is similar to the one above but with smoother transitions. For the sequence of voltages v1,v2,…,v200, one way to characterize smoothness is via the sum of squared differences:

.

When R(v) is smaller, the voltage is smoother. One way to trade off between hitting the target voltages and maintaining smoothness is to solve the regularized least squares problem

minv M(v) + λR(v),

where target−vi)2 and λ ≥ 0 is a regularization parameter. When λ is close to zero, the solution of this regularized problem is close to vtarget, but when λ is larger, the solution is considerably smoother.

Write a code to set up and solve the regularized problem for three different positive values of λ, namely, 1, 10, and 100. Plot the original target values and the smoothed solution on the same plot (one plot for each value of λ).

2. [4 pts] Spline fitting. We are running a series of experiments to evaluate the properties of a new fluorescent material. As we vary the intensity of the incident light, the material should fluoresce different amounts. Unfortunately, the material isn’t perfectly uniform and our method for measuring fluorescence is not very accurate. After testing 200 different intensities, we obtained the result below (also available in xy_data.csv). The intensities xi and fluorescences yi are recorded in the first and second columns of the data matrix, respectively.

The material has interesting nonlinear properties, and we would like to characterize the relationship between intensity and fluorescence by using an approximate model that agrees well with the trend of our experimental data. Although there is noise in the data, we know from physics that the fluorescence must be zero when the intensity is zero. This fact must be reflected in all of our models!

a) Polynomial fit. Find the best cubic polynomial fit to the data. In other words, look for a function of the form y = a1x3 + a2x2 + a3x + a4 that has the best possible agreement with the data. (Remember that the model should have exactly zero fluorescence when the intensity is zero!) Include a plot of the data along with your best-fit cubic on the same axes.

b) Spline fit. Instead of using a single cubic polynomial, we will look for a fit to the data using two quadratic polynomials. Specifically, we want to find coefficients pi and qi so that our data is well modeled by the piecewise quadratic function:

if 0 ≤ x &lt; 4 if 4 ≤ x &lt; 10

These quadratic functions must be designed so that: • as in the cubic model, there is zero fluorescence when the intensity is zero.

• both quadratic pieces have the same value at x = 4.

• both quadratic pieces have the same slope at x = 4.

In other words, we are looking for a smooth piecewise quadratic. This is also known as a spline (this is just one type of spline, there are many other types). Include a plot of the data along with your best-fit model.

3. [4 pts] Hovercraft rendezvous. Alice and Bob are cruising on Lake Mendota in their hovercrafts. Each hovercraft has the following dynamics:

Dynamics of each hovercraft:

a) Find the sequence of thruster inputs for Alice (uA) and Bob (uB) that achieves a rendezvous at t = 60 while minimizing the total energy used by both hovercraft:

total energy =

Plot the trajectories of each hovercraft to verify that they do indeed rendezvous.

b) In addition to arriving at the same place at the same time, Alice and Bob should also make sure that their velocities are both zero when they rendezvous — otherwise, they might crash! Solve the rendezvous problem again with these additional constraints on the final velocities. Is the optimal rendezvous location different from the one found in the first part?

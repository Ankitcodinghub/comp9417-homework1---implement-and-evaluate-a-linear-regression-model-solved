# comp9417-homework1---implement-and-evaluate-a-linear-regression-model-solved
**TO GET THIS SOLUTION VISIT:** [COMP9417-Homework1 – implement  and evaluate a linear regression model Solved](https://www.ankitcodinghub.com/product/comp9417-homework1-implement-and-evaluate-a-linear-regression-model-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;50363&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP9417-Homework1 -&nbsp;implement &nbsp;and evaluate a linear regression model Solved&nbsp;&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Introduction

In &nbsp;this &nbsp;homework, &nbsp;you &nbsp;work &nbsp;on &nbsp;a &nbsp;learning &nbsp;problem &nbsp;where &nbsp;you &nbsp;have &nbsp;to &nbsp;implement &nbsp;a &nbsp;linear &nbsp;regression &nbsp;model &nbsp; and &nbsp;evaluate &nbsp;it. &nbsp; &nbsp; &nbsp; You &nbsp;will &nbsp;use &nbsp;a &nbsp;publicly &nbsp;available &nbsp;dataset &nbsp;“Advertising &nbsp;Data” &nbsp;which &nbsp;consists &nbsp;of &nbsp;the &nbsp;sales &nbsp;of &nbsp;a &nbsp;product &nbsp;in &nbsp;200 &nbsp; different &nbsp;markets, &nbsp;along &nbsp;with &nbsp;advertising &nbsp;budgets &nbsp;for &nbsp;the &nbsp;product &nbsp;in &nbsp;each &nbsp;of &nbsp;those &nbsp;markets &nbsp;for &nbsp;three &nbsp; different &nbsp;media: &nbsp;TV, &nbsp;radio, &nbsp;and &nbsp;newspaper. &nbsp; &nbsp; &nbsp; We &nbsp;would &nbsp;like &nbsp;to &nbsp;predict &nbsp;the &nbsp;sale &nbsp;from &nbsp;the &nbsp;budgets &nbsp;spent &nbsp;on &nbsp;TV &nbsp;advertisements &nbsp;first &nbsp;and &nbsp;then &nbsp;repeat &nbsp;the &nbsp; regression &nbsp;for &nbsp;predicting &nbsp;the &nbsp;sale &nbsp;from &nbsp;radio &nbsp;and &nbsp;then &nbsp;newspaper &nbsp;advertisements. &nbsp; &nbsp; You &nbsp;can &nbsp;start &nbsp;by &nbsp;downloading &nbsp;the &nbsp;dataset &nbsp;“Advertising.csv”.

1. Pre-­‐processing: &nbsp; One &nbsp;important &nbsp;per-­‐processing &nbsp;step &nbsp;in &nbsp;most &nbsp;machine &nbsp;learning &nbsp;problems &nbsp;is &nbsp;feature &nbsp;normalisation. &nbsp;Feature &nbsp; normalisation &nbsp;is &nbsp;rescaling &nbsp;the &nbsp;features &nbsp;such &nbsp;that &nbsp;they &nbsp;all &nbsp;have &nbsp;similar &nbsp;scales. &nbsp;This &nbsp;is &nbsp;also &nbsp;important &nbsp;for &nbsp; algorithms &nbsp;like &nbsp;Gradient &nbsp;Descent &nbsp;to &nbsp;ensure &nbsp;the &nbsp;convergence &nbsp;of &nbsp;the &nbsp;algorithm.

One &nbsp;of &nbsp;the &nbsp;common &nbsp;normalisation &nbsp;techniques &nbsp;is &nbsp;called &nbsp;min-­‐max &nbsp;normalisation, &nbsp;where &nbsp;each &nbsp;feature &nbsp;is &nbsp; scaled &nbsp;to &nbsp;range &nbsp;between &nbsp;[0,1]. &nbsp;In &nbsp;this &nbsp;normalisation, &nbsp;for &nbsp;each &nbsp;feature, &nbsp;you &nbsp;have &nbsp;to &nbsp;find &nbsp;the &nbsp;minimum &nbsp;and &nbsp; maximum &nbsp;value &nbsp;in &nbsp;all &nbsp;your &nbsp;samples &nbsp;and &nbsp;then &nbsp;use &nbsp;the &nbsp;following &nbsp;formula &nbsp;to &nbsp;make &nbsp;the &nbsp;transformation: &nbsp; 𝑥!”#= 𝑥−min &nbsp;(𝑥) max𝑥−min &nbsp;(𝑥) &nbsp; After &nbsp;applying &nbsp;this &nbsp;normalisation, &nbsp;the &nbsp;minimum &nbsp;value &nbsp;of &nbsp;your &nbsp;feature &nbsp;will &nbsp;be &nbsp;0 &nbsp;and &nbsp;the &nbsp;maximum &nbsp;value &nbsp;will &nbsp; be &nbsp;1.

So, &nbsp;in &nbsp;the &nbsp;first &nbsp;step &nbsp;of &nbsp;this &nbsp;homework, &nbsp;you &nbsp;can &nbsp;start &nbsp;by &nbsp;creating &nbsp;a &nbsp;feature &nbsp;vector &nbsp;which &nbsp;includes &nbsp;the &nbsp;TV, &nbsp; radio &nbsp;and &nbsp;newspaper &nbsp;budget &nbsp;which &nbsp;are &nbsp;the &nbsp;features &nbsp;we &nbsp;will &nbsp;use &nbsp;to &nbsp;predict &nbsp;the &nbsp;sale &nbsp;and &nbsp;then &nbsp;apply &nbsp;min-­‐max &nbsp; normalisation &nbsp;to &nbsp;your &nbsp;features. &nbsp;You &nbsp;can &nbsp;test &nbsp;whether &nbsp;you &nbsp;did &nbsp;the &nbsp;normalisation &nbsp;correctly &nbsp;or &nbsp;not &nbsp;by &nbsp; checking &nbsp;the &nbsp;minimum &nbsp;and &nbsp;maximum &nbsp;value &nbsp;for &nbsp;each &nbsp;of &nbsp;your &nbsp;features.

2. Creating &nbsp;test &nbsp;and &nbsp;training &nbsp;set &nbsp; In &nbsp;this &nbsp;step, &nbsp;you &nbsp;have &nbsp;to &nbsp;create &nbsp;training &nbsp;and &nbsp;test &nbsp;sets. &nbsp;Please &nbsp;use &nbsp;the &nbsp;first &nbsp;190 &nbsp;rows &nbsp;of &nbsp;the &nbsp;data &nbsp;as &nbsp;training &nbsp; set &nbsp;and &nbsp;keep &nbsp;the &nbsp;10 &nbsp;remaining &nbsp;one &nbsp;(from &nbsp;191 &nbsp;to &nbsp;200) &nbsp;as &nbsp;test &nbsp;set &nbsp;which &nbsp;we &nbsp;will &nbsp;use &nbsp;later &nbsp;to &nbsp;evaluate &nbsp;the &nbsp; regression &nbsp;model.

3. Gradient &nbsp;descent &nbsp; &nbsp; Now &nbsp;in &nbsp;this &nbsp;part, &nbsp;you &nbsp;need &nbsp;to &nbsp;fit &nbsp;a &nbsp;regression &nbsp;model &nbsp;that &nbsp;predicts &nbsp;the &nbsp;sale &nbsp;from &nbsp;the &nbsp;budget &nbsp;spend &nbsp;on &nbsp;TV &nbsp; advertisement; &nbsp;so, &nbsp;you &nbsp;have &nbsp;to &nbsp;estimate &nbsp;the &nbsp;regression &nbsp;parameters &nbsp;𝜃 &nbsp;from &nbsp;the &nbsp;training &nbsp;set. &nbsp; &nbsp; The &nbsp;main &nbsp;objective &nbsp;of &nbsp;linear &nbsp;regression &nbsp;is &nbsp;to &nbsp;minimize &nbsp;the &nbsp;cost &nbsp;function &nbsp;𝐽(𝜃): &nbsp; 𝐽𝜃=1 𝑚 (𝑦!−ℎ!(𝑥!))! ! !!! &nbsp;Where &nbsp;in &nbsp;this &nbsp;homework: &nbsp; ℎ!𝑥=𝜃!𝑥!+𝜃!𝑥! &nbsp;s uch &nbsp;that &nbsp;𝑥!=1, &nbsp;and &nbsp;𝑥! &nbsp;corresponds &nbsp;to &nbsp;TV &nbsp;advertisement &nbsp;budget &nbsp;feature. &nbsp; In &nbsp;batch &nbsp;gradient &nbsp;descent, &nbsp;you &nbsp;can &nbsp;update &nbsp;the &nbsp;parameters &nbsp;iteratively &nbsp;using &nbsp;the &nbsp;following &nbsp;update &nbsp;rule: &nbsp; 𝜃!≔𝜃!+𝛼 &nbsp;1 𝑚 (𝑦!−ℎ!𝑥!)𝑥! (!)!! !! &nbsp;Please &nbsp;write &nbsp;a &nbsp;piece &nbsp;of &nbsp;code &nbsp;to &nbsp;estimate &nbsp;parameters &nbsp; 𝜃 &nbsp;for &nbsp;the &nbsp;advertising &nbsp;problem. &nbsp; &nbsp;You &nbsp;can &nbsp;set &nbsp;the &nbsp;initial &nbsp;value &nbsp;of &nbsp; your &nbsp;parameters &nbsp;as &nbsp;(𝜃!=−1, &nbsp;𝜃!=−0.5) &nbsp;and &nbsp;also &nbsp;use &nbsp;the &nbsp;learning &nbsp;rate &nbsp;of &nbsp;𝛼 =0.01 &nbsp;and &nbsp;maximum &nbsp;iteration &nbsp;of &nbsp;500.

4. Visualization &nbsp; You &nbsp;can &nbsp;visualize &nbsp;the &nbsp;changes &nbsp;in &nbsp;you &nbsp;cost &nbsp;function &nbsp;𝐽(𝜃), &nbsp;at &nbsp;each &nbsp;iteration. &nbsp;You &nbsp;just &nbsp;need &nbsp;to &nbsp;compute &nbsp;the &nbsp; value &nbsp;for &nbsp;your &nbsp;cost &nbsp;function &nbsp;at &nbsp;each &nbsp;step &nbsp;using &nbsp;the &nbsp;value &nbsp;of &nbsp;your &nbsp;parameters &nbsp;at &nbsp;that &nbsp;step &nbsp;and &nbsp;then &nbsp;plot &nbsp;your &nbsp; cost &nbsp;function &nbsp;over &nbsp;iteration &nbsp;steps.

5. Evaluation &nbsp; Now, &nbsp;it &nbsp;is &nbsp;time &nbsp;to &nbsp;evaluate &nbsp;your &nbsp;estimated &nbsp;regression &nbsp;model &nbsp;on &nbsp;the &nbsp;training &nbsp;and &nbsp;test &nbsp;data &nbsp;using &nbsp;one &nbsp;of &nbsp;the &nbsp; evaluation &nbsp;metrics. &nbsp;Here, &nbsp;you &nbsp;can &nbsp;use &nbsp;Root &nbsp;Mean &nbsp;Squared &nbsp;Error &nbsp;(RMSE): &nbsp; 𝑅𝑀𝑆𝐸= 1 𝑚 (𝑦!−𝑦(!))! ! !!! &nbsp; Compute &nbsp;the &nbsp;RMSE &nbsp;once &nbsp;for &nbsp;the &nbsp;training &nbsp;set &nbsp;and &nbsp;once &nbsp;for &nbsp;the &nbsp;test &nbsp;set &nbsp;to &nbsp;see &nbsp;if &nbsp;your &nbsp;model &nbsp;generalises &nbsp;well &nbsp; on &nbsp;unseen &nbsp;samples &nbsp;or &nbsp;not.

6. Repeating &nbsp;for &nbsp;the &nbsp;other &nbsp;two &nbsp;features &nbsp; Now, &nbsp;in &nbsp;this &nbsp;part &nbsp;of &nbsp;exercise, &nbsp;you &nbsp;want &nbsp;to &nbsp;compare &nbsp;your &nbsp;model &nbsp;with &nbsp;other &nbsp;models &nbsp;that &nbsp;use &nbsp;the &nbsp;radio &nbsp; advertising &nbsp;budget &nbsp;or &nbsp;newspaper &nbsp;advertising &nbsp;budget. &nbsp;In &nbsp;this &nbsp;step, &nbsp;you &nbsp;just &nbsp;need &nbsp;to &nbsp;repeat &nbsp;the &nbsp;step &nbsp;3 &nbsp; (Gradient &nbsp;descent) &nbsp;to &nbsp;find &nbsp;the &nbsp;parameters &nbsp;for &nbsp;predicting &nbsp;the &nbsp;sale &nbsp;once &nbsp;using &nbsp;only &nbsp;radio &nbsp;feature &nbsp;and &nbsp; once &nbsp;using &nbsp;only &nbsp;newspaper &nbsp;feature.

Now &nbsp;evaluate &nbsp;these &nbsp;two &nbsp;new &nbsp;models &nbsp;on &nbsp;the &nbsp;test &nbsp;set &nbsp;and &nbsp;compare &nbsp;your &nbsp;three &nbsp;regression &nbsp;models &nbsp;to &nbsp;see &nbsp; which &nbsp;one &nbsp;gives &nbsp;the &nbsp;best &nbsp;prediction &nbsp;on &nbsp;your &nbsp;test &nbsp;set.

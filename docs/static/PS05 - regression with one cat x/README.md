# Bert's Comments/Edits:

* **Overall**:
    + Could you include the data wrangling code that created your bit.ly csv file in the new `PS05/PS05_data_wrangling.R` file? This way I can reproduce the `hate_crimes` data frame later on if need be.
    + I would definitely include a note that because of alphanumeric ordering, the levels of `trump_support` are ordered `high`, `low`, `medium`, and hence the baseline group is `high`. Also tell them that using intermediate data wrangling, we can "reorder" the levels to be the more natural `low`, `medium`, `high`.
    + Could you add a questions making explicit that the fitted value y_hat for each level is the group mean for that level? Maybe by making them compute a `group_by(trump_support) %>% summarize(mean_hate_crimes = mean(hate_crimes))`? Perhaps in Q3.E for example?
    
* **Formatting**:
    + Could you always include a blank line after all `# section`, `## subsection`, and `### subsubsection` header lines?
    + Wrapping `***` with `<br>` seems to yield three stars in the html, and not a horizontal line. I've removed all surrounding `<br>`'s around `***`
    + Equations: In Question 3E notice how:
        + I changed the indicator function notation (for Trump support low and medium)? I made this match up with what's in moderndive so that students don't get confused.
        + I changed your three separate equations to a single one with `begin{aligned}` to have three equations aligned by the equal sign.  
        + Could you do the same for all other indicator functions and series of equations for the rest of PS?

**Individual sections**

* Setup: Could you include the cutoffs that define the levels for each of the three categorical variables?
* Question 4: Perhaps instead of gerrymandering, we could suggest a more conservative explanation of "measuring at the unit level of the state is misleading as it ignores any rural vs urban differences within states"? I'm not sure how gerrymandering, which involves congresstional districting, comes into play here? Happy to chat more about this.
* Question 6: I'm going to remove the "Trump is evil" title. While I don't disagree, I feel kind of uncomfortable making explicit political statements like this one in publicly facing documents. 
* As always, the side-by-side comparison of the before/after my suggestions is [here](https://github.com/rudeboybert/moderndive_labs/pull/6/files?utf8=%E2%9C%93&diff=split&w=1)

**Response**

I did not save any code for making csv... I put all csv files on repo. Also, if you copy and paste the "published" url into a web brower it downloads the data for you. 

I did everything you suggested in **overall** section 

I did everything in **formatting** section 

I did everything in **sections** section 

Please know I **only** made the solution file so that **I** could print it for grading. The students would **not** have (**will not**) see it. I know better than that. 

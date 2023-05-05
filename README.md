Download Link: https://assignmentchef.com/product/solved-cse6242-homework-2-tableau-d3-graphs-and-visualization
<br>
Q1. Designing a good table. Visualizing data with Tableau.

Setting Up Tableau

Tableau has provided us with student licenses for <em>Tableau Desktop</em>, available for Mac and Windows. Go to <a href="https://www.tableau.com/">Tableau</a> and select “Products/Tableau Desktop”. After installation, you will be asked to provide an activation key, which you can find on the Canvas page for this assignment. This key is for your use in this course only. <strong>Do not share the key with anyone.</strong> If you already have Tableau installed on your machine, for example from a previous trial, you may use this key to reactivate it.

If you do not have access to a Mac or Windows machine, please use the 14-day trial version of <em>Tableau Online</em>:

<ol>

 <li>Visit <a href="https://www.tableau.com/trial/tableau-online">https://www.tableau.com/trial/tableau</a><a href="https://www.tableau.com/trial/tableau-online">–</a><a href="https://www.tableau.com/trial/tableau-online">online</a></li>

 <li>Enter your information (name, email, GT details, etc.)</li>

 <li>You will then receive an email to access your Tableau Online site</li>

 <li>Go to your Site and create a workbook</li>

</ol>




One final option, if neither of the above methods work, is to take advantage of <a href="https://www.tableau.com/academic/students">Tableau for Students</a><a href="https://www.tableau.com/academic/students"><strong>.</strong></a> Follow the link and select “Get Tableau For Free”. You should be able to receive an activation key which offers you a one-year use of Tableau Desktop at no cost by providing a valid Georgia Tech email. Note that it is unclear whether Tableau intends for these licenses to be renewable, so you may only be eligible to receive one in the event that you have never used a <em>Tableau for Students</em> license before.




<strong>Connecting to the Data </strong>

Complete all parts of Q1 using <strong>a single Tableau workbook</strong>. (Technically, you could use multiple workbooks, but we do not recommend that here. The directions below assume you are using one workbook.)

<ol>

 <li>You will need a data.world account (created using any email you want) to access the data for Q1.</li>

 <li>Q1 will require connecting Tableau to multiple data sources. You can connect multiple data sources within one workbook by following the <a href="https://kb.tableau.com/articles/howto/connecting-multiple-data-sources-without-joining-or-blending">directions here</a><a href="https://kb.tableau.com/articles/howto/connecting-multiple-data-sources-without-joining-or-blending">.</a></li>

 <li>Open Tableau and when prompted to connect to a data source choose To a Server – <strong>Web Data Connector</strong>. You may need to select “More…” to see Web Data Connector as an option.</li>

 <li>Enter <a href="https://tableau.data.world/?dataset_name=mjpetrey%2Fboardgamegeek&amp;query=SELECT%20*%20FROM%20popular_board_game&amp;queryType=SQL">this URL</a> (with SQL query embedded) to connect to part of the <a href="https://data.world/mjpetrey/boardgamegeek">world data set on board</a> <a href="https://data.world/mjpetrey/boardgamegeek">games</a><a href="https://data.world/mjpetrey/boardgamegeek">.</a> This data will be used in Q1a and Q1b. You may be prompted to log in to data.world and authorize Tableau. Do not edit the provided SQL query.</li>

 <li>We recommend renaming the data connection since you will have multiple connections to mjpetrey/boardgamegeek. Rename the connection to something that makes sense to you. (Clicking on the text lets you edit it.)</li>

 <li>Click to create a new worksheet, and Tableau will then automatically create a data extract. You now have the data needed for Q1a and Q1b! (Live data connections are not an option when connecting to data.world. You can read a comparison of Tableau’s data connection options <a href="https://www.thedataschool.co.uk/ellen-blackburn/connecting-to-data-extract-or-live/">here</a><a href="https://www.thedataschool.co.uk/ellen-blackburn/connecting-to-data-extract-or-live/">.</a>)</li>

 <li>To add a new data source Click on Data – <strong>New Data Source</strong>. Then repeat steps 3-6 using <a href="https://tableau.data.world/?dataset_name=mjpetrey%2Fboardgamegeek&amp;query=SELECT%20*%20FROM%20games_detailed_info_filtered&amp;queryType=SQL">this URL</a> for Q1c.</li>

</ol>

If you are unable to connect to data.world for any reason, flat data files for Q1 have also been provided in the skeleton folder. The preferred data source is connecting online as that provides valuable experience (and something you may choose to use in your final projects). The provided csv files are identical to those hosted online and can be loaded directly into Tableau. That is, if data.world does not work for you, use the csv files.

<ol>

 <li> <strong>Good table design. </strong>You want to help a board game design company to analyze the current popular board game data from the website BoardGameGeek. Create a well-designed table to visualize the data contained in <em>csv</em>. You can use any tool (e.g., Excel, HTML, Tableau) to create the table. If you choose to use a tool other than Tableau to make the table, you will still need to load the same data into Tableau for use in Q1b.</li>

</ol>




The company is interested in grouping popular games into “support solo” (minimum player = 1) and

“not support solo” (minimum player &gt; 1), because single-player games require a different design strategy.




Instructions:

Your table should clearly communicate information about these two groups (games that support solo &amp; games that do not support solo) simultaneously. For each group, show:

<ol>

 <li>Total game count in each category (fighting, economic, …)</li>

 <li>The most representative game (game with the most ratings) in each category. If more than one game have the same ratings, pick the game that you prefer.</li>

 <li>Average rating of games in each category, rounded to the nearest 2 decimal places</li>

 <li>Average playtime of games in each category, rounded to the nearest 2 decimal places</li>

 <li>In the bottom left corner below your table include your GT username. In Tableau, this can be done by including a caption when exporting an image of a worksheet or by adding a text box to a dashboard.</li>

</ol>

Refer to the tutorial <a href="https://www.youtube.com/watch?v=yXLFo6rfiqY">here</a><a href="https://www.youtube.com/watch?v=yXLFo6rfiqY">.</a>

<ol start="6">

 <li><strong>Save the table as table.png </strong></li>

 <li>In Tableau, to save a worksheet image, go to Worksheet – Export – Image. And to save a dashboard image, go to Dashboard – Export Image (Do not simply take a screenshot since your image should have a high resolution).</li>

</ol>




<strong>Note: If there is no game under a particular group and category, think about how to visually represent missing data in your table.</strong>







You may decide on the most meaningful column names to use, the number of columns, and the column order. Keep suggestions from lecture in mind when designing your table. You are not limited to use only the techniques described in lecture. For OMS students, the online lecture video pertaining to this topic is <em>Week 4 – Fixing Common Visualization Issues – Fixing Bar Charts, Line Charts</em>. For campus student, please review slide 52 and onwards of the <a href="https://poloclub.github.io/cse6242-2020fall-campus/slides/CSE6242-510-VisFix.pdf">lecture slides</a><a href="https://poloclub.github.io/cse6242-2020fall-campus/slides/CSE6242-510-VisFix.pdf">.</a>

<em> </em>

<ol>

 <li><strong>Grouped bar chart. </strong>You want to help this board game design company better understand the relationship between game playtime and game category among popular board games. Visualize <em>csv</em> as a grouped bar chart. Your chart should display game category (e.g., fighting, economic) along the horizontal axis and game count along the vertical axis. Also show game playtime (e.g., &lt;=30, (30, 60]) for each game category.</li>

</ol>




The main goal here is for you to get familiarized with Tableau. Thus, we keep this part more open-ended, so you can practice making design decisions. <strong>We will accept most designs from you all. </strong>We show one possible design in Figure 1a, based on the tutorial from <a href="https://kb.tableau.com/articles/howto/stacked-bar-chart-multiple-measures">Tableau</a><a href="https://kb.tableau.com/articles/howto/stacked-bar-chart-multiple-measures">,</a> and you are not limited to the techniques presented there.




Instructions:

<ol>

 <li>Your design should be a grouped bar chart. For each game category, show the game count for each game playtime.</li>

 <li>Your design should have clear labeled axes and a clear chart title. Include a legend for your chart.</li>

 <li>In the bottom left corner of your image include your GT username. In Tableau, this can be done by including a caption when exporting an image of a worksheet or by adding a text box to a dashboard. Refer to the tutorial <a href="https://www.youtube.com/watch?v=yXLFo6rfiqY">here</a><a href="https://www.youtube.com/watch?v=yXLFo6rfiqY">.</a></li>

 <li><strong>Save the chart as grouped_barchart.png</strong></li>

 <li>To save a worksheet image, go to Worksheet – Export – Image. And to save a dashboard image, go to Dashboard – Export Image (Do not simply take a screenshot since your image should have a high resolution).</li>

</ol>

<strong>Figure 1a:</strong> Example of a grouped bar chart. Your chart may appear different, and can earn full credit if it meets all stated requirements. Your submitted image should include your GT username in the bottom left.

<ol>

 <li><strong>Stacked bar chart. </strong>After understanding the relationship between game category and their playtime, the game company now wants to know the count of games in different category, and if there is any relationship between game category and how they are played (their playing mechanics). They also want to know how player size changes this information.</li>

</ol>

A stacked bar chart is one way that can help understand this kind of information, where each bar represents a game category. A bar’s length represents the total game count in that category. For a bar, its “sub bars” show how games are divided into different game mechanics. (Optional reading: the effectiveness of stacked bar charts is often debated — sometimes, <a href="https://www.smashingmagazine.com/2017/03/understanding-stacked-bar-charts/">they can be confusing, difficult to understand, and may make data</a> <a href="https://www.smashingmagazine.com/2017/03/understanding-stacked-bar-charts/">series comparisons challenging</a><a href="https://www.smashingmagazine.com/2017/03/understanding-stacked-bar-charts/">.</a>)




Instructions<strong>:</strong>

<ol>

 <li>Create a ‘Worksheet’ with a stacked bar chart that shows game count for each game’s playing mechanics (sub-bars) for each game category</li>

 <li>Your chart should display game counts along the vertical axis and category along the horizontal axis</li>

 <li>Your design should have clear axes labels and a clear chart title. Include a legend for your chart.</li>

 <li>Create a <strong>dashboard </strong>using the sheet you created in the step 1</li>

 <li>Add a filter for number of ‘Max.Players’ allowed in each game. Then update the chart using this filter to generate the following chart images (Refer to the tutorial on how to add filter in a dashboard <a href="https://kb.tableau.com/articles/howto/adding-filters-to-dashboards">here</a><a href="https://kb.tableau.com/articles/howto/adding-filters-to-dashboards">.</a> Make sure to add ‘Max.Players’ in the filter shelf in the Worksheet first, like <a href="https://help.tableau.com/current/pro/desktop/en-us/filtering.htm#drag-dimensions-measures-and-date-fields-to-the-filters-shelf">this</a><a href="https://help.tableau.com/current/pro/desktop/en-us/filtering.htm#drag-dimensions-measures-and-date-fields-to-the-filters-shelf">.</a>):

  <ol>

   <li>Select “2 Players” only in the filter. Save the resulting chart as ‘<strong>png</strong>’</li>

   <li>Select “4 Players” only in the filter. Save the resulting chart as ‘<strong>png</strong>’</li>

   <li>Both images should include your GT username in the bottom left. This can be added using a text box. Refer to the tutorial <a href="https://www.youtube.com/watch?v=yXLFo6rfiqY">here</a><a href="https://www.youtube.com/watch?v=yXLFo6rfiqY">.</a></li>

  </ol></li>

 <li>To save a dashboard image, go to Dashboard – Export Image. Do not submit screenshots.</li>

</ol>




<strong>Figure 1b</strong>: Example of a stacked bar chart after selecting “4 Players” in Max.Players filter. Your chart may appear different, and can earn full credit if it meets all the stated requirements. Your submitted image should include your GT username in the bottom left.

<strong>Q1 Deliverables: </strong>

<strong>The directory structure should be as follows: </strong>

<strong>Q1/</strong>

table.png  grouped_barchart.png stacked_barchart_1.png stacked_barchart_2.png

<ul>

 <li><strong>png </strong>– An image/screenshot of the table in Q1.a (png format <strong>only</strong>).</li>

 <li><strong>png </strong>– An image of the chart in Q1.b</li>

 <li><strong>png</strong> – An image of the chart in Q1.c after filtering data for Max.Players = 2</li>

 <li><strong>png</strong> – An image of the chart in Q1.c after filtering data for Max.Players = 4</li>

</ul>

<strong>Note: </strong>Your Tableau workbooks will not be graded. Your images should be clear and of high resolution.

<h1>Q2 Force-directed graph layout</h1>

You will experiment with many aspects of D3 for graph visualization. To help you get started, we have provided the graph.html file (in the Q2 folder) and an undirected graph dataset of boardgames, board_games.csv file (in the Q2 folder). The dataset for this question had inspiration from this post on reddit <a href="https://www.reddit.com/r/boardgames/comments/9aphuw/a_network_visualization_of_the_board_game/">network visualization using boardgames</a> in which the author calculates the similarity between board games based on categories and game mechanics where the edge value between each board game (node) is the total weighted similarity index. This dataset has been modified and simplified for this question and does not fully represent actual data found from this post.

<strong>Note:</strong> You are welcome to split graph.html into graph.html, graph.css, and graph.js. Make sure that all paths in your code are <strong>relative paths</strong>. Nonfunctioning code will result in a <strong>five point deduction. </strong>

<ol>

 <li><strong> Adding node labels</strong>: Modify graph.html to show the node label (the node name, i.e., the source) at the <strong>top right</strong> of each node in <strong>bold</strong>. If a node is dragged, its label must move with it.</li>

 <li> <strong>Styling edges</strong>: Style the edges based on the “value” field in the links array:

  <ul>

   <li>If the value of the edge is equal to 0 (similar), the edge should be <strong>gray, thick, </strong>and <strong>solid</strong>.</li>

   <li>If the value of the edge is equal to 1 (not similar), the edge should be <strong>green, thin, </strong>and <strong>dashed</strong>.</li>

  </ul></li>

</ol>

<ol>

 <li><strong>Scaling nodes:</strong>

  <ol>

   <li>Scale the radius of each node in the graph based on the degree of the node (you may try linear or squared scale, but you are not limited to these choices).</li>

  </ol></li>

</ol>

<strong>Note:</strong>Regardless of which scale you decide to use, you should avoid extreme node sizes, which will likely lead to low-quality visualization (e.g., nodes that are mere points, barely visible, or of huge sizes).

<strong>Note:</strong> D3 v5 does not support d.weight (which was the typical approach to obtain node degree in D3 v3). You may need to calculate node degrees yourself. Example relevant approach is <a href="https://stackoverflow.com/questions/43906686/d3-node-radius-depends-on-number-of-links-weight-property">here</a><a href="https://stackoverflow.com/questions/43906686/d3-node-radius-depends-on-number-of-links-weight-property">.</a>

<ol start="2">

 <li>The degree of each node should be represented by varying colors. Pick a meaningful color scheme (hint: color gradients). There should be at least 3 color gradations and it must be visually evident that the nodes with a higher degree use darker/deeper colors and the nodes with lower degrees use lighter colors. You can find example color gradients at <a href="http://colorbrewer2.org/">Color Brewer</a><a href="http://colorbrewer2.org/">.</a></li>

 <li><strong> Pinning nodes</strong>:

  <ol>

   <li><strong> </strong>Modify the code so that dragging a node will fix the node’s position such that it will not be modified by the graph layout algorithm (note: pinned nodes can be further dragged around by the user). Node pinning is an effective interaction technique to help users spatially organize nodes during graph exploration. The d3 API for pinning nodes have evolved over time. We recommend reading <a href="https://stackoverflow.com/questions/10392505/fix-node-position-in-d3-force-directed-layout">this</a> <a href="https://stackoverflow.com/questions/10392505/fix-node-position-in-d3-force-directed-layout">post</a> when you work on this sub-question.</li>

  </ol></li>

</ol>

<ol start="2">

 <li>Mark pinned nodes to visually distinguish them from unpinned nodes, e.g., show pinned</li>

</ol>

nodes in a different color, border thickness or visually annotated with an “asterisk” (*), etc.

<ol start="3">

 <li><strong> </strong>Double clicking a pinned node should unpin (unfreeze) its position and unmark it. When a node is no longer pinned, it should move freely again.</li>

 <li><strong>Add GT username: </strong>Add your Georgia Tech username (usually includes a mix of letters and numbers, e.g., gburdell3) to the top right corner of the force-directed graph (see example image).</li>

</ol>

<strong>Figure 2a. </strong>Example of Visualization with pinned node (yellow). Your chart may appear different, and can earn full credit if it meets all the stated requirements.

<strong>Q2 Deliverables:</strong>

<strong>The directory structure should be as follows: </strong>

<strong>Q2/</strong>

graph.(html / js / css)

board_games.csv




<ul>

 <li><strong>(html / js / css) </strong>– the html file created, and the js / css files (if you decide to save js and css in their own separate files)</li>

 <li><strong>csv</strong> – the dataset</li>

</ul>




<h1>Q3  Line Charts</h1>

Use the dataset provided in the file <em>boardgame_ratings.csv</em> (in the Q3 folder) to create line charts.

Refer to the tutorial for line chart <a href="https://bl.ocks.org/gordlea/27370d1eea8464b04538e6d8ced39e89">here</a><a href="https://bl.ocks.org/gordlea/27370d1eea8464b04538e6d8ced39e89">.</a>

<strong>Note:</strong> You will create four charts in this question, which should be placed one after the other <strong>on a single HTML page</strong>, similar to the example image below (Figure 3). Note that your design need NOT be identical to the example.

<ol start="3">

 <li> <strong>Creating line chart.</strong> Create a line chart (Figure 3a) that visualizes the number of board game ratings from November 2016 to August 2020 (inclusively), for the eight board games: [‘Catan’, ‘Dominion’, ‘Codenames’, ‘Terraforming Mars’, ‘Gloomhaven’, ‘Magic: The Gathering’, ‘Dixit’, ‘Monopoly’]. Use D3 <a href="https://github.com/d3/d3-scale-chromatic#schemeTableau10">Tableau10 color scheme</a> to differentiate these board games. Add each board game’s name next to its corresponding line. For the x-axis, show a tick label for every three months. Use D3 <a href="https://github.com/d3/d3-scale#tickFormat">tickFormat()</a> and <a href="https://github.com/d3/d3-time-format">d3.timeFormat()</a> to format the ticks to display abbreviated months and years. For example, Jan 17, Apr 17, Jul 17. (See Figure 3a and its x-axis ticks).</li>

</ol>

<ul>

 <li>Chart title: Number of Ratings 2016-2020</li>

 <li>Horizontal axis label: Month. Use <a href="https://github.com/d3/d3-scale#scaleTime">scaleTime()</a><a href="https://github.com/d3/d3-scale#scaleTime">.</a></li>

 <li>Vertical axis label: Num of Ratings. Use a linear scale (for this part a).</li>

</ul>

<ol>

 <li><strong> Adding board game rankings.</strong> Create a line chart (Figure 3b) for this part (append to the HTML page) whose design is a variant of what you have created in part a. Start with your chart from part a. Modify the code to visualize how the rankings of [‘Catan’, ‘Codenames’, ‘Terraforming Mars’, ‘Gloomhaven’] change over time by adding a symbol with the ranking text on their corresponding lines. Show the symbol for every three months, similar to the x-axis ticks in part a. (See Figure 3b). Add a legend to explain what this symbol represents next to your chart (See the Figure 3b bottom right).</li>

</ol>

<ul>

 <li>Chart title: Number of Ratings 2016-2020 with Rankings</li>

</ul>

<ol start="3">

 <li><strong>Axis</strong> <strong>scales in D3. </strong>Create two line charts (Figure 3c-1,2) for this part (append to the HTML page) to try out two axis scales in D3. Start with your chart from part b. Then modify the vertical axis scale for each chart: the first chart uses the square root scale for its vertical axis (only), and the second chart uses the log scale for its vertical axis (only). Keep the symbols and the symbol legend you implemented in part b. At the bottom right of the last chart, add your <strong>GT username</strong> (e.g. gburdell3, see Figure 3c-2 for example). In <strong>txt, </strong>explain when we may want to use such nonlinear scales as square root scale and log scale in charts, in no more than 50 words.</li>

</ol>

<strong>Note:</strong> the horizontal axes should be kept in linear scale, and only the vertical axes are affected. <strong>Hint:</strong> You may need to carefully set the scale domain to handle the 0s in data.




<table width="509">

 <tbody>

  <tr>

   <td width="48">■ </td>

   <td width="461">First chart (Figure 3c-1)○ Chart title: Number of Ratings 2016-2020 (Square root Scale) ○ This chart uses the <strong>square root</strong> scale for its vertical axis (only) ○ Other features should be the same as part b.</td>

  </tr>

  <tr>

   <td width="48">■</td>

   <td width="461">Second chart (Figure 3c-2)○ Chart title: Number of Ratings 2016-2020 (Log Scale) ○ This chart uses the <strong>log scale</strong> for its vertical axis (only) ○ Other features should be the same as part b.</td>

  </tr>

 </tbody>

</table>










<strong>Figure 3a</strong>: Example line chart. Your chart may appear different, and can earn full credit if it meets all stated requirements.







<strong>Figure 3b</strong>: Example of a line chart with rankings. Your chart may appear different, and can earn full credit if it meets all stated requirements.







<strong>Figure 3c-1</strong>: Example of a line chart using square root scale. Your chart may appear different, and can earn full credit if it meets all stated requirements.







<strong>Figure 3c-2</strong>: Example of a line chart using log scale. Your chart may appear different, and can earn full credit if it meets all stated requirements.

<strong> </strong>

<strong>Q3 Deliverables:</strong>

<strong>The directory structure should be organized as follows:</strong>

<strong>Q3/</strong>     boardgame_ratings.csv     linecharts.(html / js / css)     linecharts.pdf

explanation.txt




<ul>

 <li><strong>csv </strong>– the dataset.</li>

 <li><strong>(html / js / css) </strong>– the html file created, and the js / css files (if you decide to save js and css in their own separate files).</li>

 <li><strong>pdf </strong>– a PDF document showing the screenshots of the four line charts created above (one</li>

</ul>

for Q3.a, one for Q3.b and two for Q3.c). You should print the HTML page as a PDF file, and each PDF page shows one chart (<strong>hint:</strong> <a href="https://stackoverflow.com/questions/1664049/can-i-force-a-page-jump-in-html-printing/1664058">use CSS page break</a><a href="https://stackoverflow.com/questions/1664049/can-i-force-a-page-jump-in-html-printing/1664058">)</a>. Clearly title the charts as instructed (see examples in Figure 3). Make sure your Georgia Tech username that you added in the last chart (see example figure 3c-2) is shown in this PDF document.

<ul>

 <li><strong>txt </strong>– the text file explaining your observations for Q3.c.</li>

</ul>

<h1>Q4  Interactive Visualization</h1>

Use the dataset average-rating.csv provided in the Q4 folder to create an interactive <a href="http://onlinestatbook.com/2/graphing_distributions/freq_poly.html">frequency polygon</a> line chart. This dataset contains a list of games, their ratings and supporting information like numbers of users who rated and year it was published. In the data sample below, each row under the header represents a game name, year, average rating, and number of users who rated the game.




name,year,average_rating,users_rated Codenames,2015,7.71148,51209

King of Tokyo,2011,7.23048,48611

<strong> </strong>

<ol start="7">

 <li><strong>[3 points] Create a line chart.</strong> Summarize the data by displaying the count of board games by rating for each year. Round each rating down to the nearest integer, usin<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor">g </a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor">floor()</a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor">.</a> For example, a rating of 7.71148 becomes 7. For each year, sum the count of board games by rating. Display one line for each of the 5 years (2015 – 2019) in the dataset.</li>

</ol>




All axes must automatically adjust based on the data. Do not hard-code any values.

<ul>

 <li>The vertical axis represents the count of board games for a given rating. Use a <a href="https://github.com/d3/d3-scale#linear-scales">linear scale</a><a href="https://github.com/d3/d3-scale#linear-scales">.</a></li>

 <li>The horizontal axis represents the ratings. Use a linear scale.</li>

</ul>




<ol>

 <li><strong>[3 points]</strong> <strong>Line styling, legend, title and username. </strong>

  <ul>

   <li>For each line, use a different color of your choosing. Display a filled circle for each rating-count data point.</li>

   <li>Display a legend on the right-hand portion of the chart to show how line colors map to years.</li>

   <li>Display the title “Board games by Rating 2015-2019” at the top of the chart.</li>

   <li>Add your GT username (usually includes a mix of lowercase letters and numbers, e.g., gburdell3) beneath the title (see example figure 4b).</li>

  </ul></li>

</ol>




Figure 4b shows an example line chart design. Yours may look different, and can earn full credit if it meets all stated requirements.




<strong>Note: </strong>The data provided in average-rating.csv requires some processing for aggregation. <strong>All aggregation must only be performed in JavaScript;</strong> <strong>you must </strong><strong>NOT modify </strong><strong>average-rating.csv</strong>. That is, your code should first read the data from .csv file as is, then you may process the loaded data using JavaScript.







<strong>Figure 4b:</strong> Line chart representing count of board games by rating for each year. Your chart may appear different, and can earn full credit if it meets all stated requirements.




<strong>Interactivity and sub-chart. </strong>In the next few sub-questions, you will create event handlers to detect mouseover and mouseout events over each circle that you added in Q4.b.







<strong>Figure 4c:</strong> Bar chart representing the number of users who rated the top 5 board games with the rating 6 in year 2019. Your chart may appear different, and can earn full credit if it meets all stated requirements.

<strong> </strong>

<ol>

 <li><strong>[5 points]</strong> <strong>Create a horizontal bar chart</strong>, so that when hovering over a circle, that bar chart will be shown <em>below </em>the line chart. The bar chart displays the top 5 board games that received the highest numbers of user ratings (users_rated), for the hovered year and rating. For example, hovering over the rating-6 circle for 2019 will display the bar chart for the number of users who rated the top 5 board games. Figure 4c shows an example design. Show one bar per game. The bar length represents the number of users who rated the game.</li>

</ol>

Note: No bar chart should be displayed when the count of games is 0 for hovered year and rating.




Axes: All axes should automatically adjust based on the data. Do not hard-code any values.

<ul>

 <li>The vertical axis represents the board games. Sort the game names in ascending order, such that the game with the smallest users_rated is at the bottom, and the game with the highest users_rated is at the top. Some boardgame names are quite long. For each game name, display its first 10 characters (if a name has fewer than 10 characters, display them all). A space counts as a character. The horizontal axis represents the number of users who rated the game (for the hovered year and rating). Use a linear scale.</li>

 <li>Set horizontal axis label to ‘Number of users’ and vertical axis label to ‘Games’.</li>

</ul>

<strong> </strong>

<ol>

 <li><strong>[3 points] Bar styling and title</strong></li>

</ol>




<ul>

 <li>Bars: All bars should have the same color and a uniform bar thickness.</li>

 <li>Title: Display a title with the format “Top 5 Most Rated Games of &lt;Year&gt; with Rating &lt;Rating&gt;” at the top of the chart where &lt;Year&gt; and &lt;Rating&gt; are what the user hovers over in the line chart. For example, hovering over rating 6 in 2015, the title would read: “Top 5 Most Rated Games of 2015 with Rating 6”</li>

</ul>




<ol>

 <li><strong>[3 points]</strong> <strong>Mouseover Event Handling</strong></li>

</ol>




<ul>

 <li>The bar chart and its title should only be displayed during mouseover events for a circle in the line chart.</li>

 <li>The circle in the line chart should change to a larger size during mouseover to emphasize that it is the selected point.</li>

 <li>When count of games is 0 for hovered year and rating, no bar chart should be displayed. The hovered-over circle on the line graph should still change to a larger size to show it is selected.</li>

</ul>




<ol>

 <li><strong>[3 points]</strong> <strong>Mouseout Event Handling</strong></li>

</ol>




<ul>

 <li>The bar chart and its title should be hidden from view on mouseout and the circle previously mouseover-ed should return to its original size in the line chart.</li>

</ul>




The graph should exhibit interactivity similar to Figure 4f where the mouse is over the larger circle.













<strong>Figure 4f:</strong> Line chart and bar chart demonstrating interactivity. Your chart may appear different, and can earn full credit if it meets all stated requirements.




<strong>Q4 Deliverables:  </strong>

<strong>The directory structure should be as follows:</strong>

<strong>Q4/</strong>

interactive.(html/js/css)     average-rating.csv




<ul>

 <li><strong>(html/js/css) </strong>– The HTML, JavaScript, CSS to render the visualization in Q4.</li>

 <li><strong>average-rating.csv</strong> – The dataset of game information.</li>

</ul>

<h1>Q5 Choropleth Map of Board Game Ratings</h1>

Choropleth maps are a very common visualization in which different geographic areas are colored based on the value of a variable for each geographic area. You have most probably seen choropleth maps showing quantities like <a href="https://bl.ocks.org/adamjanes/6cf85a4fd79e122695ebde7d41fe327f">unemployment rates for each county in the US</a><a href="https://bl.ocks.org/adamjanes/6cf85a4fd79e122695ebde7d41fe327f">,</a> or the <a href="https://geodacenter.github.io/covid/">number of confirmed COVID</a><a href="https://geodacenter.github.io/covid/">–</a><a href="https://geodacenter.github.io/covid/">19 cases</a> <a href="https://geodacenter.github.io/covid/">per 10,000 people</a>at the county level.




We will use choropleth maps to examine the popularity of different board games across the world. We have provided two files in the Q5 folder, <strong><em>ratings-by-country.csv</em></strong> and <strong><em>world_countries.json</em></strong>.

<ul>

 <li>Each row in <em>ratings-by-country.csv</em> represents about a game’s information for a country, in the form of &lt;Game,Country,Number of Users,Average Rating&gt;, where o Game: the name of a game, e.g., Catan.

  <ul>

   <li>Country: a country in the world e.g., United States of America. o Number of Users: the number of users who have rated Game who are from Country.</li>

   <li>Average Rating: the mean rating given to Game by users who are from Country. This dataset has been preprocessed and filtered to include only those games that have been rated by more than 1000 users in the world.</li>

  </ul></li>

 <li>The <em>json </em>file is a <a href="https://github.com/topojson/us-atlas">TopoJSON</a><a href="https://github.com/topojson/us-atlas"> topology</a> containing a single geometry collection:</li>

</ul>

<em>countries</em>.




<ol>

 <li><strong> [20 points] </strong>Create a choropleth map using the provided data, and use Figure 5a and 5b as references.</li>

 <li><strong>[5 points] </strong>Dropdown lists are commonly used on dashboards to enable filtering of data. Create a dropdown list (see example in Figure 5a) to allow users to select which game’s data are displayed.

  <ul>

   <li>The list options should be obtained from the Game column of the csv file. <strong> </strong></li>

   <li>Sort the list options in alphabetical order. Set the default display value to the first option.</li>

   <li>Selecting a different game from the dropdown list should update both the choropleth map (see part 2) and the legend (see part 3) accordingly.</li>

  </ul></li>

</ol>




<ol start="2">

 <li><strong>[10 points] </strong>Load the data from <em>ratings-by-country.csv</em> and create a choropleth map such that the color of each country in the map corresponds to the <strong>average rating of the game selected in the dropdown</strong> in each country.</li>

</ol>




Use <a href="https://github.com/kristw/d3.promise">promises</a> (part of the d3.v5.min.js file present in the lib directory; there is no need to download or install anything) to easily load data from multiple files into a function, and use <a href="https://github.com/topojson/topojson">topojson</a> (present in the lib folder) to draw the map.




Many countries have no ratings for some games—these should be <strong>colored gray</strong>.




For those countries that do have ratings for the selected game, use a <a href="https://github.com/d3/d3-scale/blob/master/README.md#quantile-scales">quantile scale</a> to generate the color scheme based on the average rating by country. Color them along a gradient of exactly 4 gradations from a single hue, with darker colors corresponding to higher rating values and lighter colors correspond to lower values (see gradient examples at <a href="http://colorbrewer2.org/">Color Brewer</a><a href="http://colorbrewer2.org/">)</a>.




<strong>About Scaling Colormaps:</strong> In order to create effective visualizations that highlight patterns of interest, it is important to carefully think about the relationship between the range and distribution of values being displayed (the domain) and the color scale the values are mapped to (the range). Many types of mapping functions are possible, e.g., we could use a linear mapping where the lowest game rating is mapped to the first value in the color scheme, the highest game rating is mapped to the highest value in the color scheme, and intermediate ratings are mapped to hues in the middle. <a href="https://earthobservatory.nasa.gov/blogs/elegantfigures/2014/07/29/adjusting-the-range-how-to-scale-data/">This</a> <a href="https://earthobservatory.nasa.gov/blogs/elegantfigures/2014/07/29/adjusting-the-range-how-to-scale-data/">article</a> illustrates the value of choosing appropriate endpoints for linear color maps, or log-scaling the domain so that large but relatively infrequent values do not cause differences between smaller values to be washed out. In our case, most board games have similar average ratings across countries, e.g. Catan has an average rating close to 9.3 in almost all countries, making it challenging to perceive relative differences in popularity. To address this, we can compute <a href="https://observablehq.com/@d3/quantile-quantize-and-threshold-scales#:~:text=Quantiles%20are%20defined%2C%20in%20statistics,with%20respect%20to%20the%20initial">quantiles of the</a> <a href="https://observablehq.com/@d3/quantile-quantize-and-threshold-scales#:~:text=Quantiles%20are%20defined%2C%20in%20statistics,with%20respect%20to%20the%20initial">domain data</a><a href="https://observablehq.com/@d3/quantile-quantize-and-threshold-scales#:~:text=Quantiles%20are%20defined%2C%20in%20statistics,with%20respect%20to%20the%20initial">—</a>game rating values that divide the ordered list of average ratings per country into roughly equally-sized groups. Here, we will get 4 groups, a special case of quantiles called

“quartiles” since the data are divided into quarters.




<ol start="3">

 <li><strong>[5 points]</strong> Add a <strong>vertical</strong> legend showing how colors map to the average rating for a particular game. You must use <strong>exactly 4</strong> color gradations in your submission. You could use <a href="https://d3-legend.susielu.com/">d3</a><a href="https://d3-legend.susielu.com/">–</a><a href="https://d3-legend.susielu.com/">legend.min.js</a> (in the <strong>lib </strong>folder) to create the legend for the scale you use. Also, <strong>display your GT username</strong> (e.g., gburdell3) beneath the map.</li>

</ol>




<ol>

 <li><strong> [5 points]</strong> Add a tooltip using the <a href="https://github.com/Caged/d3-tip">d3</a><a href="https://github.com/Caged/d3-tip">–</a><a href="https://github.com/Caged/d3-tip">tip.min</a> library (in the <strong>lib</strong> folder). On hovering over a country, the tooltip should show the following information on separate lines: (1) country name, (2) game, (3) number of users form the country who rated the game, and (3) average rating for that game in that country (Figure 5b demonstrates this for Catan). The tooltip should appear when the <strong>mouse </strong>hovers over the country. On mouseout, the tooltip should disappear. Position the tooltip a small distance away from the <strong>mouse cursor</strong>, which will prevent the tooltip from “flickering” as you move the mouse around quickly (the tooltip disappears when your mouse leaves a state and enters the tooltip’s bounding box). Please ensure that the tooltip is fully visible (i.e., not clipped, especially near the page edges). If the tooltip becomes clipped you may lose points.</li>

</ol>

<strong>Note:</strong> You <strong>must </strong>create the tooltip by <strong>only </strong>using <strong>d3-tip.min.js </strong>in the<strong> lib </strong>folder.







<strong>Figure 5a:</strong> Reference example for Choropleth Map showing average rating of Catan. Your chart may appear different and earn full credit as long as it meets all stated requirements.







<strong>Figure 5b:</strong> Reference example for Choropleth Map showing tooltip. Your chart may appear different and earn full credit as long as it meets all stated requirements.







<strong>Figure 5c:</strong> Reference example showing updated Choropleth and legend for Azul. Your chart may appear different and earn full credit as long as it meets all stated requirements.




<strong>Q5 Deliverables:</strong>

<strong>The directory structure should be organized as follows: </strong>

<strong>Q5/</strong>

choropleth.(html/js/css)     ratings-by-country.csv     world_countries.json




<ul>

 <li><strong>(html /js /css</strong>)- The html/js/css file to render the visualization.</li>

 <li><strong>ratings-by-country.csv</strong> – The datasets used to show the information of each state. <strong>world_countries.json </strong>– Dataset needed to draw the map.</li>

</ul>




<h1><strong>Extremely Important:</strong> folder structure &amp; content of submission zip file</h1>

We understand that some of you may work on this assignment until just prior to the deadline, rushing to submit your work before the submission window closes.  <strong>Please take the time</strong> to validate that <strong>all files</strong> are present in your submission and that you have not forgotten to include any deliverables!  If a deliverable is not submitted, you will receive <strong>zero </strong>credit for the affected portion of the assignment — this is a very sad way to lose points, since you have already done the work!




You are submitting a single <strong>zip </strong>file <strong>HW2-GTusername.zip</strong> (e.g., HW2-jdoe3.zip).




The files included in each question’s folder have been clearly specified at the end of the question’s problem description.




The zip file’s folder structure must exactly be (when unzipped):







HW2-GTUsername/     lib/         d3.v5.min.js         d3-tip.min.js

d3-geo-projection.v2.min.js         d3-dsv.min.js         d3-legend.min.js         topojson.v2.min.js     Q1/         table.png          grouped_barchart.png         stacked_barchart_1.png         stacked_barchart_2.png     Q2/

graph.(html / js / css)         board_games.csv     Q3/

linecharts.(html / js / css)         linecharts.pdf         boardgame_ratings.csv         explanation.txt     Q4/

interactive.(html / js / css)

average-rating.csv     Q5/

choropleth.(html / js / css)         ratings-by-country.csv         world_countries.json
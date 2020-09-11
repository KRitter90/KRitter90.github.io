<!-- KRitter90.github.io -->
<!-- DOCTYPE html -->
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title> This is the debugging testpage </title>
  </head>
  <body>
    <p>Here I will try to make my first log in form using html coding. </p>
    <section>
      <h2> Section 1 </h2>
      <ol>
        <li> learn different tags to get familiar with listing options </li>
        <li> coding an ordered list could be helpful</li>
        <li> be aware that an unordered list also exists </li>
      </ol>
    </section>
    <section>
      <h2> Section 2 </h2>
      Here, I will also add a paragraph. So why am I doing all of this?
        There are so many ways to learn new things for free.
        I think that is super fun. Here I will break the line:
      <br> When breaking a line, no ending tag is needed. It works just like this. 
        So Let's say I want to write even more and make the reader put some extra focus on the next line. What will happen if I add a "hr"?
      <hr> The hr also does not require any ending tag. So what is the difference between "br" and "hr"? 
      So maybe, let's just end this paragraph for now.
        <section>
          <h4> Subsection 2.1 </h4>
            <p> So this is how to write a nice looking subsection. No containers or pictures needed - it actually works with simple text formatting tips. I am very glad that I just found out and can now try more how to use them accurately. I guess less is sometimes more. </p> 
        </section>
        <section>
          <h4> Subsection 2.2 </h4>
            <p> Some more text in the next sub section. I could easily call this a Chapter... </p> 
        </section>    
    </section>
    <section> 
      <h2> Section 3: How to use different tags in html </h2>
      <p> I think here I will quickly use different tags to see how they look like once compiled. </p>
         <section> 
          <h4> Subsection 3.1 : How to use the tag: button </h4>
          <p> Now I will make a button </p>
          <button id="my_first_button" name="button_no_one" value="click">click me!
          </button>
          <p> Now I will make a second button! <br> Can I also make a button here? 
            <button id="my_second_button" name="button_no_two" value="click2">click me 2!
            </button></p>
          </section> 
      <!-- This section is about the meter-tag-->
          <section> 
            <h4> Subsection 3.2 : How to use the tag: meter </h4>
            <p> Now I will make a meter </p>
            <label for="my_first_meter">This is the label for the first meter</label>
            <meter id="my_first_meter" min="0" max="20" value="4">This is 4 out of 20 </meter><br>
            <p> Now I will make a second meter with more lines in it! <br> Can I also make a meter after the end of this paragraph?</p>
            <label for="my_second_meter">This is the label for the second meter</label>
            <meter id="my_second_meter" min="0" max="20" value="12">This is 12 out of 20 </meter>
            and directly one more
            <meter id="my_third_meter" min="0" max="20" value="8">This is 8 out of 20 </meter> <br>
            <meter min="0" max="20" value="13">This is 13 out of 20 </meter> 
            <meter min="0" max="20" value="7">This is 7 out of 20 </meter> <hr>
            Alright so let's say I want to show the current process of my self-written homepage. For this, I would like to add progress instead of meter. <br>
            So let's go to the next subsection
          </section>
          <!-- This section is about the progress-tag-->
          <section> 
            <h4> Subsection 3.3 : How to use the tag: progress </h4>
            <p> So here is now the overview if my current progress of the self-written webpage </p>
              <label for="progress1">Added all pages.</label>
              <progress id="progress1" value="84" max="100"> 84% </progress> <br>
              <label for="progress2">Made a user log-in form.</label>
              <progress id="progress2" value="0" max="100"> 0% </progress> <br>
              <label for="progress3">Coding in html5.</label>
              <progress id="progress3" value="98" max="100"> 98% </progress> <br><hr>
          </section> 
   </section>
   <section>
     <h2> The final step to make users sign-in or register </h2>
     <p> Alright. So here is now the few steps on how to build the log-in form how I want it to be on the web-page. <br></p>
     <h3> Step 1: Sign-in form </h3>
     <!-- add here the form -->
      <form action="/action_page.php" method="get">
        <label for="user_or_e-mail">user name | e-mail:</label><br>
        <input type="text" id="user_or_e-mail" name="user" value="enter user name or e-mail..."><br><br>
        <label for="pw">Password:</label><br>
        <input type="password" id="pw" name="pw" value="enter your password"><br><br>
        <input type="submit" value="Submit"><br>
        Not a member yet?
        <button id="button_form" name="button_form">register</button><br>
        (C) 2020 Ritter90. 
      </form>
      <h3> Step 2: Registration form </h3>
       <form action="/action_page.php" method="get"><hr>
        <!-- Name of the user -->
        Enter your name here:<br>
        <input type="text" id="fname" name="fname" value="First Name" required>
        <input type="text" id="lname" name="lname" value="Last Name" required><br><br>
        <!-- Address -->
        Enter your address here:<br>
          <!-- Street -->
          <input type="text" id="street_1" name="street_1" value="street name" required><br>
          <input type="text" id="street_2" name="street_2" value="house number" {1-3}[0-9] required><br>
          <input type="text" id="street_3" name="street_3" value="..."><br><br>
          <input type="text" id="street_4" name="street_4" value="post code" {4-5}[0-9] required><br><br>
          <!-- City -->
          <label for="city">Choose your City from the list:</label><br>
          <input list="cities" name="city" id="city" required>
            <datalist id="cities">
              <option value="Copenhagen">
              <option value="Aarhus">
              <option value="Odense">
              <option value="Aalborg">
              <option value="Esbjerg">
              <option value="Randers">
              <option value="Kolding">
              <option value="Horsens">
              <option value="Vejle">
            </datalist> 
          <!-- Country -->
          <label for="country">Country:</label><br>
          <input type="text" id="country" name="country" value="Denmark"><br><br>
        <!-- Contact Details -->  
         <label for="e-mail">Enter your Email:</label><br>
         <input type="email" id="email" name="email" value="info@ritterplants.com"><br><br>
        <!-- Birthday -->
         <label for="birthday">Birthday:</label>
         <input type="date" id="birthday" name="birthday"> <hr>
         How do you want to contribute to the free plant trading community?
        <!-- Add some check boxes here -->
          <input type="checkbox" id="user_role1" name="user_role1">
          <label for="user_role1"> plant trader </label><br>
          <input type="checkbox" id="user_role2" name="user_role2">
          <label for="user_role2"> plant sitter </label><br>
          <input type="checkbox" id="user_role3" name="user_role3">
          <label for="user_role3"> host for events</label><br><br>
        <!-- Submit -->
        <input type="submit" value="Submit">  <input type="reset"><hr>
        Go back to log-in?
        <button id="button_reg_log-in" name="button_reg_log-in">log-in</button><br>
        (C) 2020 Ritter90. 
      </form>    
   </section>
 </body>  
  <aside>
    <p>Where does the aside paragraph end up at?</p>
  </aside>
  
  <footer>  <hr> This is my footer. Will it be at the end of the webpage?
    <nav>
      <p> How about I add a navigation part inside my footer? </p>
    </nav>
  </footer>
  
</html>

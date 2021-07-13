<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://fonts.googleapis.com/css2?family=Sriracha&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@600&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Caveat:wght@700&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="style.css" />

    <title>Dating...</title>
  </head>

  <body>
    <div class="main">
      <div>
        <h1 class="title">Application for permission to date a Woman</h1>
      </div>
      <h3 id="description">
        <b>Note:</b> Form is to be completed at least 21 days prior to date
      </h3>

      <div class="border">
        <fieldset class="field">
          <legend class="persona">Personal Details :-</legend>
          <div class="jkl">
            <h3 class="name">
              Name:-&nbsp;&nbsp;<input class="inputop"
                type="text"
                placeholder="Enter your Name"
              />
            </h3>

            <h3 class="address">
              Address:-&nbsp;&nbsp;<input class="inputop"
                type="text"
                placeholder="Enter your Address"
              />
            </h3>

            <h3 class="email">
              Email:-&nbsp;&nbsp;<input class="inputop"
                type="email"
                placeholder="Enter your Email"
              />
            </h3>

            <h3 class="phone">
              Phone no:-&nbsp;&nbsp;<input class="inputop"
                cype="number"
                placeholder="Enter your phone no"
              />
            </h3>
          </div>

          <h3 class="iq">
            IQ:-&nbsp;&nbsp;<input class="inputop" cype="number" placeholder="Enter your IQ" />
          </h3>

          <h3 class="gender">Gender:</h3>

          <label class="radio" for="male"
            ><input type="radio" name="gen" id="male" />&nbsp;Male</label
          >
          <label class="radio" for="female"
            ><input type="radio" name="gen" id="female" />&nbsp;Female</label
          >
          <label class="radio" for="Other"
            ><input type="radio" name="gen" id="Other" />&nbsp;Other</label
          >

          <label class="date" for="start"
            >Date of Proposed Outing:
            <input class="inputop" type="date" id="start" name="trip-start"
          /></label>
        </fieldset>
      </div>

      <div class="boorder">
        <h3 class="h3">Check All That Apply</h3>
        <div class="div">
          <label class="info" for="1"
            ><input type="checkbox" name="gg" id="1" />&nbsp;I have tattoos
            and/or piercings</label
          >
          <label class="info" for="2"
            ><input type="checkbox" name="gg" id="2" />&nbsp;I am more than 2
            years older than my daughter</label
          >
          <label class="info" for="3"
            ><input type="checkbox" name="gg" id="3" />&nbsp; I own a panel van
            or V8 ute</label
          >
          <label class="info" for="4"
            ><input type="checkbox" name="gg" id="4" />&nbsp;I work
            full-time</label
          >
          <label class="info" for="5"
            ><input type="checkbox" name="gg" id="5" />&nbsp;My parents are
            rich</label
          >
          <label class="info" for="6"
            ><input type="checkbox" name="gg" id="6" />&nbsp;Is the date at a
            well lit public location</label
          >
        </div>
      </div>

      <div class="boorder">
        <label class="opt" for="cars">Political Persuasion:</label>
        <select class="selectop" name="cars" id="cars">
          <option class="valueop" value="Left wing">Left wing</option>
          <option class="valueop" value="Right wing">Right wing</option>
          <option class="valueop" value="Conservative">Conservative</option>
          <option class="valueop" value="Nazi">Nazi</option>
        </select>

        <label class="opt" for="ars">Education Level Completed:</label>
        <select class="selectop" name="ars" id="ars">
          <option class="valueop" value="University">University</option>
          <option class="valueop" value="College">College</option>
          <option class="valueop" value="High School">High School</option>
          <option class="valueop" value="None">None</option>
        </select>
      </div>

      <div class="border">
        <fieldset class="field">
          <legend class="persona">Essay Section:</legend>
          <h3 class="h3">
            In 50 words or more explain why you want to date my daughter
          </h3>
          <textarea
            class="textar"
            placeholder="Enter text Here"
            name="gh"
            id=""
            cols="50"
            rows="3"
          ></textarea>

          <h3 class="h3">Please upload contact details for 2 references</h3>
          <textarea
            class="textar"
            placeholder="Enter text Here"
            name="gh"
            id=""
            cols="50"
            rows="3"
          ></textarea>
        </fieldset>
      </div>
      <button class="butt">Send Your Application</button>
    </div>
  </body>
</html>

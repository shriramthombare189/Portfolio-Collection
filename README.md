<div style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; max-width: 800px; margin: 0 auto;">

  <!-- Animated Header -->
  <h1 align="center" style="font-size: 2.8rem; color: #2d3436; margin-bottom: 20px; 
      text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
      animation: fadeIn 1.5s ease-in-out, colorShift 8s infinite alternate;">
    Portfolio-Collection 🚀
  </h1>

  <!-- Welcome Section -->
  <div style="background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%); 
              padding: 25px; border-radius: 15px; margin-bottom: 30px; 
              box-shadow: 0 6px 12px rgba(0,0,0,0.1);
              animation: slideUp 1s ease-out;">
    <p style="font-size: 1.2rem; line-height: 1.6; color: #2d3436; text-align: center;">
      Welcome to the Portfolio-Collection repository! This project is a curated compilation of diverse and creative portfolio source code, providing a space for developers to showcase their work and inspire others in the community.
    </p>
  </div>

  <!-- How to Rate Section -->
  <div style="margin: 50px 0; animation: fadeIn 1.5s ease-in-out 0.5s both;">
    <h2 style="font-size: 2rem; color: #6c5ce7; text-align: center; 
               padding-bottom: 10px; border-bottom: 3px dashed #a29bfe;
               position: relative;">
      How to Rate: 🌟
      <span style="position: absolute; bottom: -15px; left: 50%; transform: translateX(-50%);
                  font-size: 1.5rem;">👇</span>
    </h2>

    <div style="background: white; border-radius: 15px; padding: 25px; margin-top: 30px;
                box-shadow: 0 10px 20px rgba(108, 92, 231, 0.1);
                transition: transform 0.3s ease, box-shadow 0.3s ease;"
         onmouseover="this.style.transform='translateY(-5px)'; this.style.boxShadow='0 15px 30px rgba(108, 92, 231, 0.2)'"
         onmouseout="this.style.transform=''; this.style.boxShadow='0 10px 20px rgba(108, 92, 231, 0.1)'">
      
      <ol style="padding-left: 20px; list-style-type: none; counter-reset: step-counter;">
        <li style="margin-bottom: 25px; position: relative; padding-left: 45px;
                   counter-increment: step-counter;">
          <div style="position: absolute; left: 0; top: 0; width: 30px; height: 30px;
                     background-color: #6c5ce7; color: white; border-radius: 50%;
                     display: flex; align-items: center; justify-content: center;
                     font-weight: bold;">
            <span style="color: white;">1</span>
          </div>
          <strong style="color: #2d3436; font-size: 1.1rem;">Login with GitHub:</strong>
          <p style="margin-top: 5px; color: #636e72;">
            Log in with your GitHub account on 
            <a href="https://repo-rater.eddiehub.io/" 
               style="color: #6c5ce7; text-decoration: none; font-weight: 500;">
              Repo Rater
            </a> 🚀
          </p>
        </li>

        <li style="margin-bottom: 25px; position: relative; padding-left: 45px;
                   counter-increment: step-counter;">
          <div style="position: absolute; left: 0; top: 0; width: 30px; height: 30px;
                     background-color: #6c5ce7; color: white; border-radius: 50%;
                     display: flex; align-items: center; justify-content: center;
                     font-weight: bold;">
            <span style="color: white;">2</span>
          </div>
          <strong style="color: #2d3436; font-size: 1.1rem;">Add Rating:</strong>
          <p style="margin-top: 5px; color: #636e72;">
            Navigate to the "Add Rating" section 🌐
          </p>
        </li>

        <li style="margin-bottom: 25px; position: relative; padding-left: 45px;
                   counter-increment: step-counter;">
          <div style="position: absolute; left: 0; top: 0; width: 30px; height: 30px;
                     background-color: #6c5ce7; color: white; border-radius: 50%;
                     display: flex; align-items: center; justify-content: center;
                     font-weight: bold;">
            <span style="color: white;">3</span>
          </div>
          <strong style="color: #2d3436; font-size: 1.1rem;">Paste Repository Link:</strong>
          <p style="margin-top: 5px; color: #636e72;">
            Paste the link to this repository: 
            <a href="https://github.com/avinash201199/Portfolio-Collection" 
               style="color: #6c5ce7; text-decoration: none; font-weight: 500;">
              Portfolio-Collection
            </a> 🔗
          </p>
        </li>

        <li style="margin-bottom: 25px; position: relative; padding-left: 45px;
                   counter-increment: step-counter;">
          <div style="position: absolute; left: 0; top: 0; width: 30px; height: 30px;
                     background-color: #6c5ce7; color: white; border-radius: 50%;
                     display: flex; align-items: center; justify-content: center;
                     font-weight: bold;">
            <span style="color: white;">4</span>
          </div>
          <strong style="color: #2d3436; font-size: 1.1rem;">Provide Rating:</strong>
          <p style="margin-top: 5px; color: #636e72;">
            Give your rating based on your experience ⭐
          </p>
        </li>

        <li style="position: relative; padding-left: 45px;
                   counter-increment: step-counter;">
          <div style="position: absolute; left: 0; top: 0; width: 30px; height: 30px;
                     background-color: #6c5ce7; color: white; border-radius: 50%;
                     display: flex; align-items: center; justify-content: center;
                     font-weight: bold;">
            <span style="color: white;">5</span>
          </div>
          <strong style="color: #2d3436; font-size: 1.1rem;">Submit:</strong>
          <p style="margin-top: 5px; color: #636e72;">
            Submit your rating 📝
          </p>
        </li>
      </ol>
    </div>
  </div>

  <!-- CSS Animations -->
  <style>
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes slideUp {
      from { 
        opacity: 0;
        transform: translateY(30px);
      }
      to { 
        opacity: 1;
        transform: translateY(0);
      }
    }
    @keyframes colorShift {
      0% { color: #2d3436; }
      25% { color: #6c5ce7; }
      50% { color: #00b894; }
      75% { color: #e84393; }
      100% { color: #fd79a8; }
    }
    .pulse {
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }
  </style>

  <!-- Contribution Section -->
  <div style="background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%); 
              padding: 30px; border-radius: 15px; margin: 50px 0;
              text-align: center; animation: slideUp 1s ease-out 0.5s both;"
       class="pulse">
    <h2 style="font-size: 2rem; color: #d63031; margin-bottom: 15px;">
      Contribution is fun! 💚
    </h2>
    <p style="font-size: 1.1rem; line-height: 1.6; color: #2d3436;">
      In order to make a hassle-free environment, I implore you all (while contributing) to follow the instructions mentioned below!
    </p>
    <p style="font-size: 1.3rem; font-weight: bold; color: #2d3436; margin-top: 15px;">
      Happy Submissions 🙂
    </p>
    <p style="font-size: 1.1rem; line-height: 1.6; color: #2d3436; margin-top: 15px;">
      Your feedback is valuable! Thank you for contributing to the growth of the Portfolio-Collection repository. Happy rating! 🌈✨
    </p>
  </div>

</div>

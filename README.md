
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Artificial Intelligence (AI) - Comprehensive Research by Gouransh Pankaj</title>
<style>
  /* Reset & base */
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #f9fbfd;
    color: #222;
    line-height: 1.7;
  }
  a {
    color: #0066cc;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  /* Navbar */
  nav {
    position: sticky;
    top: 0;
    background: #003366;
    padding: 1rem 2rem;
    z-index: 1000;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: white;
    flex-wrap: wrap;
  }
  nav .logo {
    font-weight: 700;
    font-size: 1.8rem;
    letter-spacing: 2px;
    user-select: none;
  }
  nav ul {
    list-style: none;
    display: flex;
    gap: 1.5rem;
    margin: 0;
    padding: 0;
    flex-wrap: wrap;
  }
  nav ul li {
    cursor: pointer;
  }
  nav ul li:hover {
    text-decoration: underline;
  }
  /* Hero */
  .hero {
    min-height: 90vh;
    background: linear-gradient(135deg, #0059b3, #3399ff);
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 0 2rem;
    text-align: center;
  }
  .hero h1 {
    font-size: 3.8rem;
    margin-bottom: 1rem;
    font-weight: 900;
    animation: fadeInDown 1s ease forwards;
  }
  .hero p {
    font-size: 1.4rem;
    max-width: 700px;
    margin: 0 auto 2rem auto;
    animation: fadeInUp 1s ease forwards;
  }
  @keyframes fadeInDown {
    0% {opacity: 0; transform: translateY(-40px);}
    100% {opacity: 1; transform: translateY(0);}
  }
  @keyframes fadeInUp {
    0% {opacity: 0; transform: translateY(40px);}
    100% {opacity: 1; transform: translateY(0);}
  }
  /* Sections */
  section {
    max-width: 900px;
    margin: 4rem auto;
    background: white;
    padding: 2.5rem 3.5rem;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
  }
  section h2 {
    margin-top: 0;
    color: #0059b3;
    border-bottom: 3px solid #0059b3;
    padding-bottom: 0.6rem;
    font-weight: 700;
    font-size: 2.2rem;
  }
  section p, section ul, section ol {
    font-size: 1.15rem;
    margin-bottom: 1.3rem;
  }
  ul, ol {
    padding-left: 2rem;
  }
  /* Cards */
  .cards {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(300px,1fr));
    gap: 2rem;
    margin-top: 1.5rem;
  }
  .card {
    background: #e6f0ff;
    border-radius: 12px;
    padding: 1.8rem 2rem;
    box-shadow: 0 4px 12px rgba(0,89,179,0.2);
    transition: transform 0.3s ease;
  }
  .card:hover {
    transform: translateY(-8px);
  }
  .card h3 {
    margin-top: 0;
    color: #003366;
    font-size: 1.3rem;
  }
  /* Collapsible FAQ */
  .collapsible {
    background-color: #0059b3;
    color: white;
    cursor: pointer;
    padding: 1.2rem 1.5rem;
    width: 100%;
    border: none;
    border-radius: 10px;
    text-align: left;
    font-size: 1.2rem;
    margin-top: 1.5rem;
    user-select: none;
    transition: background-color 0.3s ease;
  }
  .collapsible:hover {
    background-color: #004080;
  }
  .active, .collapsible:active {
    background-color: #00264d;
  }
  .content {
    padding: 1.2rem 1.5rem;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.4s ease;
    background: #cce0ff;
    border-radius: 0 0 10px 10px;
    margin-bottom: 1.5rem;
    font-size: 1.1rem;
    color: #003366;
    line-height: 1.6;
  }
  /* Embedded videos */
  .video-container {
    margin-top: 2rem;
    position: relative;
    padding-bottom: 56.25%; /* 16:9 ratio */
    height: 0;
    overflow: hidden;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0,89,179,0.3);
  }
  .video-container iframe {
    position: absolute;
    top: 0; left: 0;
    width: 100%;
    height: 100%;
    border: none;
  }
  /* Footer */
  footer {
    text-align: center;
    padding: 3rem 1rem;
    background: #003366;
    color: white;
    margin-top: 6rem;
    font-size: 1rem;
    letter-spacing: 1px;
  }
  /* Responsive */
  @media (max-width: 650px) {
    nav ul {
      flex-direction: column;
      gap: 1rem;
      margin-top: 0.5rem;
    }
    .hero h1 {
      font-size: 2.8rem;
    }
    section {
      padding: 1.8rem 2rem;
      margin: 2.5rem 1rem;
    }
  }
</style>
</head>
<body>

<nav>
  <div class="logo">AI Research by Gouransh Pankaj</div>
  <ul>
    <li><a href="#intro">Introduction</a></li>
    <li><a href="#history">History</a></li>
    <li><a href="#types">Types of AI</a></li>
    <li><a href="#ml">Machine Learning</a></li>
    <li><a href="#dl">Deep Learning</a></li>
    <li><a href="#applications">Applications</a></li>
    <li><a href="#ethics">Ethics & Challenges</a></li>
    <li><a href="#future">Future</a></li>
    <li><a href="#faq">FAQs</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<section class="hero" id="intro">
  <h1>Artificial Intelligence (AI): Comprehensive Research</h1>
  <p>Welcome to this detailed research on Artificial Intelligence — a transformative technology reshaping industries, societies, and our daily lives. Explore the origins, types, cutting-edge advancements, and ethical considerations of AI.</p>
  <div class="video-container" title="Intro to AI by CrashCourse">
    <iframe src="https://www.youtube.com/embed/2ePf9rue1Ao" allowfullscreen></iframe>
  </div>
</section>

<section id="history">
  <h2>History of Artificial Intelligence</h2>
  <p>The journey of Artificial Intelligence dates back to ancient mythology, but its formal scientific development began in the 20th century:</p>
  <ul>
    <li><strong>Ancient Roots:</strong> Myths of automatons and mechanical beings that mimic human actions date back to Greek, Chinese, and Egyptian cultures.</li>
    <li><strong>1950 - Turing Test:</strong> Alan Turing published "Computing Machinery and Intelligence," introducing the Turing Test to assess machine intelligence. (<a href="https://en.wikipedia.org/wiki/Turing_test" target="_blank">More on Turing Test</a>)</li>
    <li><strong>1956 - Dartmouth Conference:</strong> The term "Artificial Intelligence" was coined at this pivotal conference by John McCarthy and others, marking AI as a formal field.</li>
    <li><strong>1960s-70s - Early AI Programs:</strong> Development of programs such as ELIZA (a natural language processor) and Shakey the Robot, the first mobile intelligent robot.</li>
    <li><strong>1980s - Expert Systems:</strong> AI began being applied to practical problems using rule-based "expert systems" like MYCIN for medical diagnosis.</li>
    <li><strong>AI Winters:</strong> Periods of reduced funding and interest in AI research during late 1970s and late 1980s due to limited progress.</li>
    <li><strong>1997 - Deep Blue:</strong> IBM’s chess-playing computer defeated world champion Garry Kasparov, showcasing AI’s strategic abilities.</li>
    <li><strong>2010s - Deep Learning Boom:</strong> AI breakthroughs in speech recognition, image classification, natural language processing, and autonomous vehicles through neural networks.</li>
  </ul>
  <p>For a deep dive, check the comprehensive <a href="https://plato.stanford.edu/entries/artificial-intelligence/" target="_blank">Stanford Encyclopedia of Philosophy on AI</a>.</p>
</section>

<section id="types">
  <h2>Types of Artificial Intelligence</h2>
  <p>AI can be broadly categorized by capability and functionality:</p>
  <div class="cards">
    <div class="card">
      <h3>Narrow AI (Weak AI)</h3>
      <p>AI systems designed to perform a single task very well, such as language translation, facial recognition, or game playing. Examples include Siri, Alexa, and Google Translate.</p>
    </div>
    <div class="card">
      <h3>General AI (Strong AI)</h3>
      <p>A theoretical AI with intelligence equal to humans across virtually all tasks — capable of reasoning, learning, and understanding complex concepts.</p>
    </div>
    <div class="card">
      <h3>Superintelligent AI</h3>
      <p>An advanced form of AI that surpasses human intelligence in all domains. Currently hypothetical and a topic of ethical debate and research.</p>
    </div>
    <div class="card">
      <h3>Reactive Machines</h3>
      <p>Basic AI that reacts to inputs but has no memory or past experience reference, such as IBM’s Deep Blue chess computer.</p>
    </div>
    <div class="card">
      <h3>Limited Memory AI</h3>
      <p>AI systems that use historical data to make decisions, for example, self-driving cars analyzing traffic patterns.</p>
    </div>
    <div class="card">
      <h3>Theory of Mind AI (Future Goal)</h3>
      <p>AI that can understand human emotions, beliefs, intentions, and thought processes — a complex, future development.</p>
    </div>
    <div class="card">
      <h3>Self-aware AI (Speculative)</h3>
      <p>AI that has its own consciousness and self-awareness, a theoretical idea still beyond current science.</p>
    </div>
  </div>
</section>

<section id="ml">
  <h2>Machine Learning: The Heart of Modern AI</h2>
  <p>Machine Learning (ML) is a subset of AI that focuses on teaching machines to learn from data and improve their performance over time without being explicitly programmed for every task.</p>
  <h3>How Machine Learning Works</h3>
  <p>ML algorithms identify patterns within data and use these patterns to make predictions or decisions.</p>
  <ul>
    <li><strong>Supervised Learning:</strong> Learning from labeled datasets (input-output pairs).</li>
    <li><strong>Unsupervised Learning:</strong> Finding hidden patterns in unlabeled data.</li>
    <li><strong>Reinforcement Learning:</strong> Learning through trial and error, receiving rewards or penalties.</li>
  </ul>
  <h3>Popular ML Algorithms</h3>
  <ul>
    <li>Linear Regression</li>
    <li>Decision Trees</li>
    <li>Support Vector Machines</li>
    <li>k-Nearest Neighbors</li>
    <li>Random Forests</li>
    <li>Neural Networks</li>
  </ul>
  <p>For beginners, <a href="https://www.coursera.org/learn/machine-learning" target="_blank">Andrew Ng’s Machine Learning course on Coursera</a> is highly recommended.</p>
  <div class="video-container" title="Machine Learning Basics by Simplilearn">
    <iframe src="https://www.youtube.com/embed/Gv9_4yMHFhI" allowfullscreen></iframe>
  </div>
</section>

<section id="dl">
  <h2>Deep Learning: Mimicking the Human Brain</h2>
  <p>Deep Learning (DL) is a specialized ML approach based on artificial neural networks inspired by the human brain’s architecture.</p>
  <h3>How Deep Learning Works</h3>
  <p>DL models consist of layers of nodes (“neurons”), each transforming input data and passing it forward, enabling the system to learn complex features and representations.</p>
  <h3>Common Deep Learning Architectures</h3>
  <ul>
    <li><strong>Convolutional Neural Networks (CNNs):</strong> Primarily used for image and video processing.</li>
    <li><strong>Recurrent Neural Networks (RNNs):</strong> Designed for sequential data such as speech and language.</li>
    <li><strong>Transformers:</strong> Modern architecture powering state-of-the-art language models like GPT and BERT.</li>
  </ul>
  <p>Deep Learning enables AI to excel at tasks such as voice assistants, autonomous vehicles, and medical image analysis.</p>
  <div class="video-container" title="Deep Learning Explained by 3Blue1Brown">
    <iframe src="https://www.youtube.com/embed/aircAruvnKk" allowfullscreen></iframe>
  </div>
</section>

<section id="applications">
  <h2>Applications of Artificial Intelligence</h2>
  <p>AI is revolutionizing numerous fields, including:</p>
  <ul>
    <li><strong>Healthcare:</strong> Disease diagnosis, drug discovery, robotic surgery.</li>
    <li><strong>Finance:</strong> Fraud detection, algorithmic trading, credit scoring.</li>
    <li><strong>Transportation:</strong> Autonomous vehicles, traffic optimization.</li>
    <li><strong>Retail:</strong> Personalized recommendations, inventory management.</li>
    <li><strong>Entertainment:</strong> Content recommendations, game AI.</li>
    <li><strong>Natural Language Processing (NLP):</strong> Chatbots, translation, sentiment analysis.</li>
    <li><strong>Smart Homes:</strong> Voice control, automation systems.</li>
  </ul>
  <p>Explore real-world AI implementations in the <a href="https://ai.google/" target="_blank">Google AI Research</a> and <a href="https://openai.com/research/" target="_blank">OpenAI Research</a> portals.</p>
</section>

<section id="ethics">
  <h2>Ethics, Challenges, and Risks of AI</h2>
  <p>As AI grows in power and ubiquity, ethical considerations are critical:</p>
  <ul>
    <li><strong>Bias and Fairness:</strong> AI systems can perpetuate or amplify human biases if trained on biased data.</li>
    <li><strong>Privacy Concerns:</strong> Use of personal data raises questions about consent and security.</li>
    <li><strong>Job Displacement:</strong> Automation may replace certain jobs, raising economic and social issues.</li>
    <li><strong>Accountability:</strong> Determining responsibility for AI decisions, especially in autonomous systems.</li>
    <li><strong>Autonomous Weapons:</strong> Ethical debates on AI in military applications.</li>
    <li><strong>Transparency:</strong> The "black-box" nature of some AI models limits explainability.</li>
  </ul>
  <p>Important organizations working on AI ethics include <a href="https://partnershiponai.org/" target="_blank">Partnership on AI</a> and <a href="https://aiethics.world/" target="_blank">AI Ethics World</a>.</p>
</section>

<section id="future">
  <h2>The Future of Artificial Intelligence</h2>
  <p>AI continues to evolve rapidly with exciting future prospects:</p>
  <ul>
    <li>Advancements in <strong>General AI</strong> aiming for machines that can perform any intellectual task humans do.</li>
    <li>Integration of AI with <strong>quantum computing</strong> for unprecedented processing power.</li>
    <li>Increasing human-AI collaboration in creative fields like art, music, and writing.</li>
    <li>AI-powered healthcare revolutionizing personalized medicine and longevity research.</li>
    <li>Smart cities using AI to improve sustainability, safety, and infrastructure.</li>
  </ul>
  <p>Learn more about future AI trends from <a href="https://www.technologyreview.com/topic/artificial-intelligence/" target="_blank">MIT Technology Review on AI</a>.</p>
</section>

<section id="faq">
  <h2>Frequently Asked Questions (FAQs)</h2>

  <button class="collapsible">What is Artificial Intelligence?</button>
  <div class="content">
    <p>Artificial Intelligence (AI) is the simulation of human intelligence processes by machines, especially computer systems, enabling them to learn, reason, and solve problems.</p>
  </div>

  <button class="collapsible">How is AI different from Machine Learning?</button>
  <div class="content">
    <p>AI is a broad field encompassing any technique enabling machines to mimic human intelligence. Machine Learning is a subset of AI focused on algorithms that learn from data.</p>
  </div>

  <button class="collapsible">Are AI systems conscious?</button>
  <div class="content">
    <p>No. Current AI systems are not conscious; they perform tasks based on algorithms without awareness or emotions.</p>
  </div>

  <button class="collapsible">Is AI dangerous?</button>
  <div class="content">
    <p>AI poses risks mainly related to misuse, bias, and job displacement, but with careful regulation and ethical design, these can be mitigated.</p>
  </div>

  <button class="collapsible">Where can I learn AI programming?</button>
  <div class="content">
    <p>Popular platforms for learning AI programming include Coursera, edX, Udacity, and freeCodeCamp, with languages such as Python being widely used.</p>
  </div>
</section>

<section id="contact">
  <h2>Contact Information</h2>
  <p>For questions, collaborations, or feedback, reach out to me:</p>
  <ul>
    <li><strong>Author:</strong> Gouransh Pankaj</li>
    <li><strong>Email:</strong> <a href="mailto:gouranshpankaj655@gmail.com">gouranshpankaj655@gmail.com</a></li>
    <li><strong>Phone:</strong> <a href="tel:+919829139988">+91 98291 39988</a></li>
  </ul>
  <p>Thank you for exploring this research on Artificial Intelligence!</p>
</section>

<footer>
  &copy; 2025 Gouransh Pankaj Research. All Rights Reserved.
</footer>

<script>
  // Collapsible FAQ functionality
  const collapsibles = document.querySelectorAll('.collapsible');
  collapsibles.forEach(button => {
    button.addEventListener('click', () => {
      button.classList.toggle('active');
      const content = button.nextElementSibling;
      if (content.style.maxHeight) {
        content.style.maxHeight = null;
      } else {
        content.style.maxHeight = content.scrollHeight + 'px';
      }
    });
  });

  // Smooth scrolling for navigation links
  document.querySelectorAll('nav a').forEach(anchor => {
    anchor.addEventListener('click', function(e){
      e.preventDefault();
      const targetID = this.getAttribute('href').substring(1);
      document.getElementById(targetID).scrollIntoView({behavior: 'smooth'});
    });
  });
</script>

</body>
</html>

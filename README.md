# Artificial Intelligence & Machine Learning in Medicine 
## Elective Guide for Students
A one month, self-paced, project-based AI/ML curriculum for fourth-year medical students.

## Course Overview
Innovations in clinical care are increasingly impacted by the development and implementation of machine learning (ML) and artificial intelligence (AI). As future clinicians, medical students should be informed and prepared for technological changes that will affect how they provide care for their patients. The goals of this senior elective are to demystify AI and ML in healthcare, enable students to have informed conversations about these technologies, participate in their clinical advancement, and optionally publish abstracts/literature reviews based on their work during the elective

This elective is offered in two tracks, Technical and Non-Technical/Conceptual. 
- Non-Technical/Conceptual Track: Most students will choose the Non-Technical track. The Non-Technical track has no prerequisites, and will not require writing code. This track also offers more flexibility in specialty choice. 
- Technical Track: Students interested in the Technical track are expected to be comfortable with coding (ex. completion of a 1 semester Intro coding course). They will design and implement projects using curated datasets provided by the elective director (current datasets include chest x ray images, mammograms, knee radiographs, or ICU data). This is intended to maximize the likelihood of student success in the limited time frame.

Students will:
Build an appreciation for the growing importance of ML in clinical use cases
Learn to identify problems in clinical practice that can be solved by ML and draft a project proposal
Understand limitations of ML/AI (biases, implementation problems, errors) and learn how to avoid pitfalls
Design, train, and evaluate basic clinical ML algorithms (Technical Track only)

All students will receive mentoring in drafting and scoping a technical project proposal for a clinical AI project on a topic of their interest. Students with a prior programming background (i.e. proficiency in Python coding) who choose the Technical track will also work on developing, training, and evaluating a clinical machine learning model using one of several provided datasets, and will receive feedback and guidance during this process. The Non-Technical track will have a deeper focus in understanding concepts, limitations, and history of clinical ML, generally and in a specialty of their choosing, and will learn how to train a basic machine learning model without writing code using an online graphical interface.

This is a self-directed elective. Students should allow their curiosity to guide their learning beyond this, and independently research the day’s topics using the plethora of online resources available. You are encouraged to tailor the elective to topics you are passionate about. 

## Details for Deliverables
### Deliverable 1: 
Literature Review: Students will complete a literature review on the state of machine learning in a field of their choosing (topic can be broad, like “ML applications in dermatology”; or narrower, like “ML algorithms to predict sepsis risk”). Students should not only demonstrate understanding of the potential of ML in this field, but also the difficulties (data limitations, implementation problems, ethics, etc). Students will submit a summary (1 page single-spaced, or slide presentation) of their learnings.

### Deliverable 2: 
Dataset Exercise: Understanding different data sources is crucial in healthcare AI. Students should begin building an intuition for what data sources can be used for particular situations and model types, as well as the strengths, weaknesses, sample size, gaps, biases, etc. present in each data source. For this exercise, students should find ~3 open-source datasets for healthcare (such as those freely available on <a href="https://www.kaggle.com/datasets?search=health">Kaggle</a> or <a href="https://huggingface.co/">Hugging Face</a>) and look through the data sources. Imagine problems that could be solved using those datasets, and prepare a written critique (1 page single-spaced per dataset) of the data source. Important factors to consider include those listed above (strengths, weaknesses, etc.) as well as consideration of future steps that could be taken to improve these existing datasets in order to effectively use them for feature selection, model training, and model validation. If you were the one collecting the data, what would you have done differently? Why might this data collection be difficult in the real world? You may want to use this exercise to explore datasets relevant to your chosen field/problem.

### Deliverable 3: 
AI Project Proposal Paper: The final deliverable for this elective is a hypothetical ML tool that you would like to see implemented in a clinical setting. For Technical track students, this paper can describe implementation of the model that was trained/validated during the elective. This can be either a paper or a slide presentation.
This well-thought out deliverable should contain detailed sections on the background and problem space including literature citations, an implementation design (including timeline, pilot/study setup with intervention and comparisons, and a facility deployment plan), outcomes (primary and secondary), analysis plan (what type of statistical analysis, metrics to track, covariates, etc), and stakeholders (which roles across which teams would be important to collaborate with). An important component of this plan is describing the current state of the clinical workflow that the tool is meant to be used in, as well as a future state describing the workflow steps including the tool and consideration of how workflow disruptions could be minimized. Any plans (educational/training, etc) detailing how staff would be encouraged to actually use the new tool may also be relevant. Lastly, ethics and equity considerations of the tool/project should be discussed. 
You are encouraged to receive input from the course director (via weekly meetings or office hours) throughout development on this deliverable. For examples, please consult with the course director.

## Elective Checklist 

To use this checklist: Copy checklist into a new document. Share your copy of the checklist with the faculty advisor, checking off LOs as you complete them. Some resources may require institutional access. 
After completing each section, take some time for independent research to answer any questions that might have come up for you. 

Your Name:_____________________              Month Started: ________________________

Required Surveys:
<ul>
<li> Pre-elective Survey: Before beginning the elective, fill out this <a href="https://forms.gle/UuA4zRZ17PgGh1GfA">Intake Form</a> (3 mins)
<li> Post-elective Survey: At the end of the month, fill out this <a href="https://forms.gle/i9haxqr3MhwADnkS6">Debrief Form</a> (8 mins)
</ul>

### LO 1: Appreciate the growing impact of machine learning (ML) in medicine. 
<ul>
<li> Watch “Machine Learning in Medicine” NEJM <a href="https://www-nejm-org.proxy.library.emory.edu/doi/10.1056/NEJMra1814259">video</a> (4 mins) + read paper (1 hr)
<li>Optional: Read “A Short Guide for Medical Professionals in the Era of Artificial Intelligence” Nature <a href="https://www.nature.com/articles/s41746-020-00333-z">paper</a> (1 hr)
</ul>

### Mini Exercise 1: Use a web interface to train a basic ML model without writing any code.
<ul>
<li>Watch Teachable Machine <a href="https://www.youtube.com/watch?v=T2qQGqZxkD0 ">video</a> (<5 mins)
<li>Download the dataset from this <a href="https://drive.google.com/drive/folders/11WXOFAnBLlDmZrHtbeGn0Qe-75o3euFw?usp=sharing">folder</a> (5 mins). This dataset contains two folders of training data, as well as a smaller folder of testing data.
<li>Train a model with the <a href="https://teachablemachine.withgoogle.com/">Teachable Machine tool</a>; upload the images in the provided dataset above, train the model, and then test it out on the testing images. 
<li>Experiment with other data types (video, audio, etc). (1 hr) 
<li>Train some models and paste a screenshot of one of your experiments here.
</ul>

### LO 2: Compare/contrast AI and ML. LO 3: State and differentiate various ML techniques (supervised vs. unsupervised learning, classification, regression, etc). LO 4: Understand what kinds of medical problems can and cannot be solved by ML.
<ul>
<li>Read <a href="https://learning-oreilly-com.proxy.library.emory.edu/library/view/hands-on-machine-learning/9781492032632/ch01.html">"Hands-On Machine Learning" textbook</a> Ch1 (2 hrs)
<li>Complete Stanford’s <a href="https://www.coursera.org/learn/fundamental-machine-learning-healthcare">"Fundamentals of Machine Learning for Healthcare" course</a> 
<ul>
<li>Why Machine Learning in Healthcare? (2 hrs)
<li>Concepts & Principles of ML in healthcare, Part 1 (2 hrs)
<li>Concepts & Principles of ML in healthcare, Part 2 (2 hrs)
<li>Evaluation and Metrics for machine learning in healthcare (2 hrs)
</ul>
<li>Copy and paste a screenshot of your completion certificate here. Do not rush through these! These videos are the conceptual foundation for many following LOs. Previous students have found this course very helpful for their projects. 
</ul>

### LO 5: Develop an intuition of how machines “learn”. Describe how neural networks are structured, trained, and evaluated. Learn vocabulary and concepts used to describe model training (loss functions, gradient descent, backpropagation).
<ul>
<li>Watch <a href="https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi">video series</a> on neural networks (2 hrs)
<li>In your own words (~1 paragraph), summarize how neural networks work.
<li>Optional: Watch Emory MedAI’s “Intro to AI” Workshop <a href="https://www.youtube.com/watch?v=7HUMJ2xYOJw&t=1452s&ab_channel=MedML">recording</a> (30 mins)
</ul>

### Mini Exercise 2: Understand the potential of Large Language Models (LLM) in medicine.
<ul>
<li>Watch “What is ChatGPT?” BBC News <a href="https://www.youtube.com/watch?v=BWCCPy7Rg-s">video </a> (8 mins)
<li>Try out <a href="https://chat.openai.com/chat">ChatGPT </a>with a range of medical and non-medical prompts; you may need to make an account; if the site is at capacity, try again later (1 hr). Here is some <a href="https://www.theatlantic.com/technology/archive/2022/12/openai-chatgpt-chatbot-messages/672411/">inspiration </a> to get started.
<li>Have a conversation with ChatGPT related to your chosen medical specialty.
<li>Paste a screenshot of a conversation with ChatGPT that surprised you.
<li>Read about <a href="https://interestingengineering.com/innovation/google-deepmind-medpalm-language-model">MedPaLM </a>, an LLM for medicine (10 mins)
</ul>

### LO 6: Understand the limitations and pitfalls of ML (reproducibility, interpretability, bias).
<ul>
<li>Read “What are radiological deep learning models actually learning?” <a href="https://jrzech.medium.com/what-are-radiological-deep-learning-models-actually-learning-f97a546c5b98">post</a> (10 mins) 
<li>Read “Shortcuts: How Neural Networks Love to Cheat” <a href="https://thegradient.pub/shortcuts-neural-networks-love-to-cheat/">post</a> (1 hr)
<li>What are some examples of “shortcut learning” that could be dangerous in your chosen specialty? 
<li>Read “Artificial Intelligence versus Clinicians: Systematic Review of Design, Reporting Standards, and Claims of Deep Learning Studies”: <a href="https://www.bmj.com/content/368/bmj.m689">paper</a> (20 mins)
</ul>

### Deliverable 1: Complete a literature review of machine learning in a field of the student’s choice. (Details above.)
<ul>
<li>Read “How to Read Articles That Use Machine Learning: Users’ Guides to the Medical Literature” <a href="https://jamanetwork.com/journals/jama/article-abstract/2754798">paper</a> (1 hr)
<li>Choose an area/specialty in which to conduct review: ________________
<li>Optional, but strongly recommended: Identify an additional mentor in this specialty who can offer domain expertise: _________________
<li>Find and read 6-10 papers addressing the questions below. (15 hrs)
<ul>
<li>How can ML be used in this field?
<li>What types of ML are used?
<li>What kinds of datasets are used?
<li>What limitations exist?
<li>What ethical considerations exist?
<li>Possible research questions for Clinical AI project proposal
</ul>
<li>Briefly summarize learnings for each paper (2-3 bullets each). Turn in summaries to the course director via email. (1 hr)
</ul>


### LO 7: Describe issues that may arise in implementation of a machine learning algorithm in clinical practice.
<ul>
<li>Read “Developing a Delivery Science for Artificial Intelligence in Healthcare” <a href="https://www.nature.com/articles/s41746-020-00318-y">paper</a> (1 hr)
</ul>

### LO 8: Discuss ethical issues that concern the use of ML in healthcare.
<ul>
<li>Read “Bias in Predictive Algorithms” <a href="https://www.khanacademy.org/computing/ap-computer-science-principles/data-analysis-101/x2d2f703b37b450a3:machine-learning-and-bias/a/bias-in-predictive-algorithms">article</a> from KhanAcademy (30 mins)
<li>Review “Can Machine Learning Solve Everything?” <a href="https://www.coursera.org/learn/fundamental-machine-learning-healthcare/lecture/hbOBE/can-machine-learning-solve-everything">video</a> from Stanford course above
<li>Read: “AI recognition of patient race in medical imaging: a modelling study”: <a href="https://www.sciencedirect.com/science/article/pii/S2589750022000632">paper</a> (30 mins)
<li>Read: “Write It Like You See It: Detectable Differences in Clinical Notes By Race Lead To Differential Model Recommendations” <a href="https://arxiv.org/abs/2205.03931">paper</a> (30 mins)
<li>Read Implementing Machine Learning in Health Care — Addressing Ethical Challenges: <a href="https://www.nejm.org/doi/full/10.1056/NEJMp1714229">paper</a> (1 hr)
<li>Read: Secure & Robust Machine Learning for Healthcare: A Survey: <a href="https://arxiv.org/pdf/2001.08103.pdf">paper</a> (1 hr)
</ul>

### Deliverable 2: Complete dataset exercise. (Details above; to see previous student’s examples, reach out to the course coordinators.)
<ul>
<li>Find ~3 open-source datasets for healthcare (such as those freely available on kaggle.com)
<li>Prepare a written critique (<1 page single-spaced) of each dataset, considering sample size, gaps, biases, etc. present in each data source
</ul>

### Deliverable 3: Draft a clinical AI project proposal. (Details above; to see previous student’s examples, reach out to the course coordinators.)
<ul>
<li>Identify a problem and an AI-based solution: ____________
<li>Discuss with faculty mentor
<li>Draft an Project Proposal to address this question (example <a href="https://reposhub.com/python/deep-learning/eugeneyan-ml-design-docs.html">outline</a>). Address:
<ul>
<li>Technical problem
<li>Stakeholders
<li>Data format and sources
<li>Training and testing steps
<li>Pilot and implementation plan
</ul>
</ul>

### Deliverable 4: *Technical Track only: Train and evaluate a clinical ML algorithm in Python. 
<ul>
<li>Refer to textbook for code samples and detailed technical guidance (<a href="https://learning-oreilly-com.proxy.library.emory.edu/library/view/hands-on-machine-learning/9781492032632/ch01.html">remainder</a> of textbook beyond Ch1)
<li>Discuss with faculty advisor
<li>Find a dataset
<li>Analyze and preprocess data
<li>Build model and write code for training
<li>Train and test model
</ul>



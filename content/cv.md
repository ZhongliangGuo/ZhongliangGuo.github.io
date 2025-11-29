You can access my complete resume in PDF [here](/CV.pdf).

## Techology Stack

- **Areas of Expertise:** AI Robustness, AI Safety, Trustworthy AI, Computer Vision, LLMs
- **Programming Languages:** Python, Java, SQL, C#, JavaScript, LaTeX, HTML5
- **Libraries & Frameworks:** PyTorch, Diffusers, OpenCV, NumPy, Pandas, Matplotlib, Django
- **Tools & Technologies:** Linux, Shell, Vim, Slurm, Docker, Git

## Education

**[University of St Andrews](https://www.st-andrews.ac.uk/)**, PhD in Computer Science, *2022 - 2025*
- Full scholarship with stipend
- Supervisors: [Dr. Ognjen Arandjelović](https://scholar.google.com/citations?&user=D7bpRJ8AAAAJ) and [Dr. Lei Fang](https://sites.google.com/view/leifangresearch/home)

**[University of St Andrews](https://www.st-andrews.ac.uk/)**, MSc in Artificial Intelligence with Distinction, *2021 - 2022*
- GPA: 16.7/20 (Distinction)
- Nominated on 2021/2022 [Dean's List](https://www.st-andrews.ac.uk/students/academic/awards/universityprizes/deanslist/)

**[Northwest University of Political Science and Law](https://en.nwupl.edu.cn/)**, BSc in Forensic Science, *2017 - 2021*
- GPA: 88.4/100 (ranked 1/55)
- Awarded 2021 Outstanding Undergraduate Dissertation

## Experience

**AIGC Algorithm Engineer (Intern)**
[DreamFace](https://dreamfaceapp.com/) AI Video Generation Team
*Sep 2025 - Oct 2025*
- **AI Agent System Development**. Designed end-to-end AI agent for automated long biographical video generation.
- Developed timeline-based storyboard generation pipeline using multi-agent coordination for long-form video creation.
- Engineered smooth video transitions using first-frame and last-frame constrained generation techniques.
- Implemented quality assessment framework with Visual Quality Assessment and vLLM evaluation metrics.
- Designed iterative refinement workflow with agent-based quality control for continuous improvement.

**Research Collaboration**
City University of Hong Kong
*Apr 2024 - Present*
- **Technical Mentor**. Serve as a technical mentor for [Prof. Chun Pong Lau](https://samuel930930.github.io/)'s lab.
- Provide academic guidance to 3 PhD students on adversarial attack/defense and diffusion-based generation.
- Participate in research ideation sessions, helping to conceptualize and validate experimental approaches.
- Contributed to 2 papers in CVPR 2025, 1 paper in Pattern Recognition, and multiple papers in writing.

**LLMs Research Fellow**
University of St Andrews (funded by Tapoly)
*Jan 2025 - Mar 2025*
- **Principal Researcher**. An AI agent based on LLMs with unique knowledge of insurance industry.
- Designed, implemented and deployed AI agent for the insurance industry to automatically solve customer needs, such as policy inquiries and intelligent claims settlement.
- Proposed a more economical AI agent implementation and deployment framework, making the response of AI agents more accurate without fine-tuning or training.
- Proposed a performance evaluation framework for multi-agent to align with the requirement of data sensitivity and data insufficiency in the insurance industry.

**Radar Algorithm Research Fellow**
University of St Andrews (funded by MathWorks)
*Dec 2023 - Nov 2024*
- **Principal Researcher**. Machine Learning based drone and bird radar detection using micro-Doppler radar signature.
- Designed and implemented physical models to simulate avian and drone dynamics.
- Conducted field experiments to collect various radar frequency data of birds and drones.
- Processed the signal data into corresponding micro-Doppler signatures and categorized, labeling a new dataset.
- Used physic-driven data transformation to reduce the redundancy and complexity of radar signal, making it machine learning-friendly with data compression rates up to 96%.
- Developed multiple usage neural network for bird-drone-clutter-noise classification and moving object tracking.

**Teaching Assistant**
University of St Andrews
*Sep 2023 - May 2025*
- Modules include [CS1002 Object-Oriented Programming](https://www.st-andrews.ac.uk/subjects/modules/catalogue/?code=CS1002), [CS3105 Artificial Intelligence](https://www.st-andrews.ac.uk/subjects/modules/catalogue/?code=CS3105), and [ID5059 Knowledge Discovery and Data Mining](https://www.st-andrews.ac.uk/subjects/modules/catalogue/?code=ID5059).
- Topics cover Programming Languages, Machine Learning, Artificial Intelligence, Deep Learning, and Statistics.
- Demonstrated lab sessions, tutorials, lectures, and marked coursework.
- Designed a seminar about AI robustness with an interactive webpage, delivering to audiences unfamiliar with the topic. [[link](https://blogs.cs.st-andrews.ac.uk/csblog/2024/11/26/pgr-seminar-with-zhongliang-guo/)]

## Research Experience

**1. Adversarial Attack for Social Good**
- **Principal Investigator**. Explored the benign use of adversarial attack in computer vision.
- Proposed an adversarial pre-processing method to protect artwork from unauthorized neural style transfer, allowing safeguarding unique style against popular transfer techniques, with a color-centric Image Quality Assessment.
- Proposed a near black-box attack method against Latent Diffusion Models, achieving SOTA performance at 4× faster than existing approaches, reducing VRAM occupation by 60%.
- Proposed a Diffusion-based facial privacy protection method using adversarial techniques.

**2. Adversarial Attack for AI Robustness**
- **Principal Investigator**. Explored the vulnerability of existing machine learning models and potential defenses.
- Exposed the illusory robustness in SOTA signature verification models, proposing a False Positive attack to address the unbalanced performance of existing attack methods.
- Proposed an attack framework against multi-modal diffusion models, utilizing distilled backbones and optimized noise predictors to generate high-fidelity adversarial examples with superior transferability and robustness against defenses.
- Proposed a one-step diffusion-based adversarial purification method using controlled purification and noise distillation, speed up 100× while maintaining 76% robustness.

**3. Large Language Models and Robustness**
- Proposed, implemented, and deployed a dual-retrieval RAG to improve the Q&A performance of LLMs in industry. Proposed a multi-agent evaluation protocol with a new data generation paradigm for industrial scenarios.
- Proposed the feature alignment enhancement paradigm and a new backdoor attack method for LLMs. The proposed method significantly improved the backdoor attack success rate while maintaining the model's conventional task reasoning performance, revealing undiscovered weaknesses of large language models.
- Proposed a new data synthesis method for backdoor attacks on Chinese LLMs, significantly improving the concealment of backdoor attacks. The proposed method achieves SOTA performance on various models and baselines.

**4. Object Counting (Supervised/Semi-Supervised/Unsupervised)**
- Used density graph estimation network architecture to effectively improve the accuracy and robustness of target counting in complex scenarios.
- For scenarios where labeling data is limited, developed a new semi-supervised learning method, using only 40% labeling data to achieve accuracy comparable to full labeling.
- Revealed that existing zero-shot methods are insensitive to text prompts, and the widely-used dataset has labeling bias. Leveraged T2I Diffusion Model to achieve text-guided, zero-shot object counting.
- Solved the problem of aberration between existing natural image and thermal image crowd counting datasets. Used unsupervised modal alignment based on visual prompts to achieve high-precision counting without natural images.

**5. Content Safety and High-Risk Scenario Assessment for Large Language Models**
- Benchmarked content safety for LLMs in public health-sensitive information provision.
- Constructed a dataset containing 2,160 QA pairs covering safety boundary check, quantitative information accuracy, and risk level reasoning.
- Exposed failure risks of existing LLM safety mechanisms in high-risk contexts.
- Demonstrated that excessive safety constraints may lead to refusal of service, compromising model availability.
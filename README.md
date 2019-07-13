# Awesome-resources
Awesome resources for Machine/Deep Learning at industry scale

## [Gradio](https://github.com/gradio-app/gradio)
Build a simple web server which allows users to interact with your machine learning model through a GUI, by wrapping your model **in just two lines of code**. Gradio also creates a shareable, public link to your model so you can share the interface with others (e.g. your client, your advisor, or your dad).
Gradio is useful for:

- Creating demos for clients
- Getting feedback from collaborators
- Debugging your model during development

## [BentoML](https://github.com/bentoml/BentoML)
?

## Data augmentation
[imgaug](https://github.com/aleju/imgaug) is one of the richest image augmentation libraries, and [albumentations](https://github.com/albu/albumentations) is one of the fastest. [CloDSA](https://github.com/joheras/CLoDSA) is the newest, and should contain even more techinques than imgaug, while covering not only 2D images but also 3D images and videos.

## Machine learning on GPU and distributed machine learning
[The power of RAPIDS and Dask combined](https://medium.com/rapids-ai/10-minutes-to-rapids-cudf-and-dask-cudf-3d16fcb84139?ncid=so-twi-n2-95701&linkId=100000006753457)

## How to manage the risks of deploying ML in production 
 - [Software Engineering for Machine Learning: A Case Study](https://www.microsoft.com/en-us/research/publication/software-engineering-for-machine-learning-a-case-study/)
    ##### Abstract
    Recent advances in machine learning have stimulated widespread interest within the Information Technology sector on integrating AI capabilities into software and services. This goal has forced organizations to evolve their development processes. We report on a study that we conducted on observing software teams at Microsoft as they develop AI-based applications. We consider a nine-stage workflow process informed by prior experiences developing AI applications (e.g., search and NLP) and data science tools (e.g. application diagnostics and bug reporting). We found that various Microsoft teams have united this workflow into preexisting, well-evolved, Agile-like software engineering processes, providing insights about several essential engineering challenges that organizations may face in creating large-scale AI solutions for the marketplace. We collected some best practices from Microsoft teams to address these challenges. In addition, we have identified three aspects of the AI domain that make it fundamentally different from prior software application domains: 1) discovering, managing, and versioning the data needed for machine learning applications is much more complex and difficult than other types of software engineering, 2) model customization and model reuse require very different skills than are typically found in software teams, and 3) AI components are more difficult to handle as distinct modules than traditional software components – models may be “entangled” in complex ways and experience non-monotonic error behavior. We believe that the lessons learned by Microsoft teams will be valuable to other organizations.

 - [Full Stack Deep Learning Bootcamp](https://fullstackdeeplearning.com/march2019) A course which teaches the full stack of production Deep Learning:
     - Formulating the problem and estimating project cost
     - Finding, cleaning, labeling, and augmenting data  
     - Picking the right framework and compute infrastructure
     - Troubleshooting training and ensuring reproducibility
     - Deploying the model at scale
     
     Students will complete a project culminating in deploying a computer vision and natural language processing system into production.

- [Hidden Technical Debt in Machine Learning Systems](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems) The paper outlines a number of pitfalls one can run into when developing ML algorithms and taking them to production, described through the software development term of 'technical debt'. The idea is that although it may be quick to get a works-well-enough ML algorithm going in an experiment, taking it into production with the same attitude can cause issues down the road, with some being more difficult to spot than others. One such example is introducing a feature to a model that produces a slight improvement, but introduces a disproportionate amount of complexity to the dataset generation. This complication of the data dependencies makes maintenance and improvement of the architecture more painful and untenable down the road, and can be difficult to avoid given deadline pressures and model performance improvement expectations from leadership.
- [The ML Test Score: A Rubric for ML Production Readiness and Technical Debt Reduction](https://ai.google/research/pubs/pub46555)
    #### Abstract
    Creating reliable, production-level machine learning systems brings on a host of concerns not found in small toy examples or even large offline research experiments. Testing and monitoring are key considerations for ensuring the production-readiness of an ML system, and for reducing technical debt of ML systems. But it can be difficult to formulate specific tests, given that the actual prediction behavior of any given model is difficult to specify a priori. In this paper, we present 28 specific tests and monitoring needs, drawn from experience with a wide range of production ML systems to help quantify these issues and present an easy to follow road-map to improve production readiness and pay down ML technical debt.    
- [Two Big Challenges in Machine Learning](https://leon.bottou.org/talks/2challenges) by the great Leon Bottou
- [Measuring operational quality of recommendations](https://www.youtube.com/watch?v=UKa87yQr2es&feature=youtu.be) a 20 min talk from a recommender systems conference: How to monitor ml/data driven services in production. This was actually used in production and it works quite well.
- [Zero to Deep Learning](https://www.zerotodeeplearning.com/) Q3-2019
- [MLOps.org](https://mlops.org/) A resource for Data Scientist, Engineers and Business leaders to understand and implement ML operationalization in the enterprise
- [How to plan and execute your ML and DL projects](https://blog.floydhub.com/structuring-and-planning-your-machine-learning-project/) the first in a series of blog posts from Floydhub on how to deploy ML models in production


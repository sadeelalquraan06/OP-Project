# Optimization Algorithms Course Project

## Project Title
Adaptation to Data Distribution Shifts and Emerging Classes Using Optimization Algorithms and XAI.

## Project Description
This project investigates how machine learning classification models respond to changes in data distributions over time and the appearance of previously unseen classes.

The project explores the use of optimization algorithms, feature selection, and Explainable Artificial Intelligence (XAI) to improve classification performance and robustness under different distribution shift scenarios.

## Project Objectives
- Analyze feature distribution shift P(X).
- Analyze label distribution shift P(Y).
- Investigate concept drift P(Y|X).
- Detect and handle emerging classes.
- Apply optimization algorithms for feature selection and hyperparameter tuning.
- Use SHAP or LIME to explain model predictions.
- Retrain classification models using XAI attribution values.
- Compare model performance using suitable evaluation metrics.

## Project Scenarios
1. Covariate Shift (P(X)).
2. Label Distribution Shift (P(Y)).
3. Concept Drift (P(Y|X)).
4. Emerging Classes.

## Optimization Algorithms
- Genetic Algorithm (GA).
- Particle Swarm Optimization (PSO).
- Simulated Annealing (SA).
- Gradient Descent (GD).
- Stochastic Gradient Descent (SGD).
- Newton's Method.

## Tools and Technologies
- Python
- Machine Learning
- Scikit-learn
- SHAP / LIME
- Git and GitHub
- Data Visualization

## Project Structure
- datasets/ : Original and processed datasets.
- notebooks/ : Data analysis and experiments.
- src/ : Python source code.
- models/ : Trained machine learning models.
- xai_datasets/ : Datasets generated from XAI attribution values.
- results/ : Experimental results and evaluation metrics.
- reports/ : Final project report.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- Macro F1-score
- Execution Time
- Convergence Behavior

## Team Members
1. Abdulrahman
2. Sadeel
3. Lana
4. Samira
5. Abdulaziz

## Submission Deadline
January 1, 2027.

## Project Status
In Progress.    


📌 **ملخص مشروع خوارزميات التحسين – OP**

**فكرة المشروع:**

المطلوب نعمل مشروع تعلم آلي يدرس كيف تتأثر نماذج التصنيف لما تتغير البيانات مع مرور الوقت، وكيف نتعامل مع ظهور فئات جديدة لم تكن موجودة سابقاً.

**المطلوب تنفيذه على مراحل:**

1️⃣ **تجهيز البيانات:**
اختيار مجموعة بيانات مناسبة، تنظيفها وتجهيزها، وتقسيمها إلى بيانات قديمة وجديدة.

2️⃣ **محاكاة التغييرات:**
نعمل أربع حالات:
- تغير خصائص البيانات.
- تغير نسب الفئات.
- تغير العلاقة بين الخصائص والنتائج.
- ظهور فئة جديدة لم تكن موجودة بالتدريب السابق.

3️⃣ **اختيار الخصائص:**
استخدام خوارزميات التحسين لاختيار أهم الخصائص التي تساعد النموذج على التصنيف.

4️⃣ **تدريب النماذج وتحسينها:**
تجربة نماذج تصنيف مختلفة، ومقارنة أدائها، واستخدام خوارزميات التحسين لضبط أفضل إعداداتها.

5️⃣ **تفسير النتائج:**
استخدام SHAP أو LIME لمعرفة مدى تأثير كل خاصية على قرارات النموذج، وإنشاء مجموعة بيانات جديدة من قيم التفسير.

6️⃣ **إعادة التدريب والتقييم:**
تدريب نموذج جديد باستخدام قيم SHAP، ثم مقارنة نتائجه مع النماذج السابقة في الحالات الأربع.

7️⃣ **التقرير النهائي:**
تجميع الأكواد والبيانات والنماذج والنتائج والجداول وكتابة التقرير النهائي.

**طريقة العمل بيننا:**
- كل عضو يشتغل على الجزء المتفق عليه.
- نرفع الأكواد والملفات على GitHub.
- كل عضو يعمل على Branch خاص فيه.
- نفتح Pull Request عند الانتهاء.
- تتم مراجعة التعديلات قبل دمجها في الفرع الرئيسي main.

📅 **آخر موعد للتسليم: 1/1/2027**

مهم جداً نتعاون ونوثق كل خطوة ونتأكد أن جميع أجزاء المشروع متكاملة.

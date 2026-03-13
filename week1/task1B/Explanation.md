1. What is Machine Learning?
    Machine Learning is a way of teaching computers to learn patterns 
    from data and make predictions, without being explicitly programmed 
    with rules. Instead of writing "if score > 80 then grade = A", 
    you show the computer thousands of examples and it figures out 
    the pattern itself.
    
2. What is Supervised Learning?
    Supervised learning is when the model is trained on labeled data —
    meaning every example has a known correct answer. The model learns
    by comparing its predictions to the correct answers and adjusting
    itself to reduce mistakes.

    Example: Training a model on student scores where we already know
    each student's total score.
    
3. What is Unsupervised Learning?
    Unsupervised learning is when the model is given data with no labels
    and has to find patterns or groupings on its own.
    
    Example: Grouping students into clusters based on similar performance
    without telling the model what the groups should be.
    
4. What are Features, Target Variable, and Training Data?

  Features: The input columns the model uses to make predictions.
  Example: math_score, lunch, parental_level_of_education.

  Target variable: The output column the model is trying to predict.
  Example: total_score.

  Training data: The portion of the dataset used to teach the model.
  The model sees these examples and learns patterns from them.
  
5. In the Student Performance dataset:

  Target: total_score — a measure of overall academic performance.

  Features: gender, lunch, test_preparation_course,
  parental_level_of_education, race/ethnicity, and the individual
  subject scores (math_score, reading_score, writing_score).
  
 NOTE = WE SHOULD NOT PROVIDE ALL THREE SCORES AS FEATURES AS THAT IS LITERALLY PROVIDING THE MODEL THE FORMULA TO CALCULATE . IT WON'T PREDICT IT'LL ANSWER. R^2 WILL ALWAYS BE 1.

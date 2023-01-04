# Cross-Validation-and-Grid-Search

Important point dicussed here is

1.  K-fold validation.

2. Cross_val_score and Cross_validate are two function which help us to automate the K-fold technique. It can be  imported from model_selection library.

3. Both Cross_val_score and Cross_validate have almost similar syntax with one difference : the prior method will accpt only a single string value for scoring matrix whereas the later method will accept the list of strings.
![image](https://user-images.githubusercontent.com/99719105/210560215-fe71df37-9e45-4889-b724-d2617ead910e.png)

![image](https://user-images.githubusercontent.com/99719105/210560382-8868aa3f-6b82-4e11-bd54-8df819c8a67b.png)

4. It will accept the above metioned parameters and returns the error scores of each iteration or folds.

5. Grid Search another techniques where the model is evaluated against the list of paramter values defined in the parameter grid. Parameter grid is in the form of the dictionary where the key refers to the parameter of the models and keys represents the list of hyper parameter value that we wish model to be trained on.

6. We will be able to obtain the best estimator or best parameter value once the model is fitted on the training data. We will be also able to see all the possible combination executed by the model and their results.
![image](https://user-images.githubusercontent.com/99719105/210561604-cd85cad7-1c36-46fb-910c-5826bc40c47e.png)




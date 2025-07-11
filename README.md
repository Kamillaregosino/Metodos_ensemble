# Comparação usando diferentes Métodos Ensemble

O dataset quer prever se o cliente fez ou não o depósito a prazo fixo após a campanha telefônica, com isso, dado o perfil do cliente e as informações da campanha, espera-se prever se o cliente vai contratar o depósito ou não.

## Random Forest

**Acurácia**

Accuracy: 0.9452

**Precision, recall, f1-score para classe 0 (Pacientes sem diabete) e classe 1 (Pacientes com diabete)**

                 precision    recall  f1-score   support

           0       0.92      0.97      0.95      7908
           1       0.97      0.92      0.94      8061

    accuracy                           0.95     15969
   macro avg       0.95      0.95      0.95     15969
weighted avg       0.95      0.95      0.95     15969

## Extra Trees

**Acurácia**

Accuracy: 0.9463

**Precision, recall, f1-score para classe 0 (Pacientes sem diabete) e classe 1 (Pacientes com diabete)**

                precision    recall  f1-score   support

           0       0.93      0.96      0.95      7908
           1       0.96      0.93      0.95      8061

    accuracy                           0.95     15969
   macro avg       0.95      0.95      0.95     15969
weighted avg       0.95      0.95      0.95     15969

## AdaBoost

Accuracy: 0.9169

**Precision, recall, f1-score para classe 0 (Pacientes sem diabete) e classe 1 (Pacientes com diabete)**

                precision    recall  f1-score   support

           0       0.90      0.94      0.92      7908
           1       0.94      0.90      0.92      8061

    accuracy                           0.92     15969
   macro avg       0.92      0.92      0.92     15969
weighted avg       0.92      0.92      0.92     15969


## Gradient Boosting 

Accuracy: 0.9381

**Precision, recall, f1-score para classe 0 (Pacientes sem diabete) e classe 1 (Pacientes com diabete)**

                 precision    recall  f1-score   support

           0       0.92      0.95      0.94      7908
           1       0.95      0.92      0.94      8061

    accuracy                           0.94     15969
   macro avg       0.94      0.94      0.94     15969
weighted avg       0.94      0.94      0.94     15969
# ML_projects
 
A collection of small, practical machine learning projects — each one built to solve a real problem rather than as a toy exercise.
 
## Projects
 
### `wifi_plan_model.ipynb`
A K-Nearest Neighbors model trained on Serbian optical internet plans (download/upload speed, price, bundle type, discount status) to recommend a good plan given a budget and speed requirement. This is the model that actually helped my dad pick a good internet provider.
 
### `mobile_device_usage_prediction.ipynb`
A linear regression model that predicts mobile device usage trends over time, filtered specifically to mobile phones. The dataset it uses, `mobile_devices.csv`, is based on data from the Republički zavod za statistiku Republike Srbije (Statistical Office of the Republic of Serbia).
 
### `credit_acceptance_model.ipynb`
A decision tree classifier that predicts whether a bank customer will accept/subscribe to a credit offer, based on features like age, job, education, loan status, and previous campaign outcome.
 
### `ssd_price_predicition_model.ipynb`
A linear regression model tracking SSD vs. HDD price trends over time to project future pricing.
 
### `ssd_recomendation_model.ipynb`
A K-Nearest Neighbors–based recommendation model for SSDs, matching drives by capacity, interface, form factor, drive class, media type, and production status.
 
## Notes
 
- The `ML_projects(No datasets)` folder contains the notebooks without their underlying data files.
- Most notebooks use `scikit-learn` (KNN, linear regression, decision trees) with `pandas` for data handling and `pickle` for model persistence.
## License
 
See [LICENSE](LICENSE).
 

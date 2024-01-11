# Energy Production and Sustainability - Kaggle Competition

The 6th edition of the ML @SBS/DAA competition centers on the development of machine learning models to predict solar panel-generated electrical energy injected into the grid hourly. Solar energy's pivotal role in clean energy transition and environmental sustainability underscores the competition's significance.

The dataset spans September 2021 to April 2023, encompassing solar panel data from Braga, Portugal. Attributes, including meteorological and geographical data, alongside historical energy metrics, empower participants to craft predictive models. "Injeção na rede (kWh)," a qualitative scale indicating energy injection levels, guides predictions with categories like None, Low, Medium, High, and Very_High.

Two energy and meteorological datasets, covering 2021 and 2022, aid model training. Participants can enhance models with additional attributes. The goal is predicting energy injection levels in the test dataset ("energia_202301-202304.csv"), using the categorical scale. Accuracy is the evaluation metric.

Participants can submit three files daily, with one chosen for the final ranking. The CSV submission must have 2256 records, matching the test dataset, with "RowId" and "Result" columns.

Notably, the XGBoost classifier and Random Forest proved effective, showcasing their prowess in optimizing energy efficiency, reducing emissions, and promoting sustainability.

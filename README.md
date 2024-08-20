# Stock-Price-pridiction-using-Deep-learning-models
Developed a machine learning-based retail sales forecasting system with 97.7% accuracy through advanced data processing. Created a Streamlit app for EDA, allowing users to explore trends and generate sales forecasts. Managed PostgreSQL database for efficient data storage, retrieval, and seamless deployment of predictive models.

Stock Price Prediction Using Deep Learning Models
Project Description:
Developed and trained multiple deep learning models to predict stock prices based on historical stock data. Implemented and compared the performance of Bidirectional LSTM, GRU, 1D CNN, and Transformer models, using Root Mean Squared Error (RMSE) as the evaluation metric.

Key Contributions:

Bidirectional LSTM Model:

Utilized Bidirectional LSTM layers to capture temporal patterns in the time series data.
Achieved an RMSE of 0.0242 on the test set, demonstrating the model's ability to predict stock prices accurately.
GRU Model:

Implemented Gated Recurrent Unit (GRU) layers to enhance computational efficiency while maintaining performance.
Achieved an RMSE of 0.0149, indicating better performance compared to the Bidirectional LSTM model.
1D CNN Model:

Designed a 1D Convolutional Neural Network (CNN) to capture local patterns in the data.
Achieved an RMSE of 0.0517, highlighting the model's ability to extract features but with lower accuracy compared to recurrent models.
Transformer Model:

Developed a custom Transformer model to leverage attention mechanisms for long-range dependencies in the data.
Achieved an RMSE of 0.5334, which, while innovative, indicated the complexity and challenges of using Transformer models for this specific time series data.
Technologies Used:
Python, TensorFlow, Keras, NumPy, Pandas, and Matplotlib.

Outcome:
The project provided valuable insights into the strengths and weaknesses of different deep learning architectures in the context of stock price prediction. The GRU model was identified as the best performer among the implemented models, achieving the lowest RMSE on the test set.

## Sentence Construction using Star Trek's Dialogue

Character level LSTM trained from Star Trek transcript, included in this repository. View Jupyter Notebook for full training sequence and model outputs.

### Model outputs after being trained for 20 epochs (max sentence length=100):

- UHURA: Aye

- Jim. He was a death of our mind

- Jim. If you do not speak to the Enterprise is the signal do we have in the same in the ship. I seem t

- ENGINEER: There is a dead ship is stranged one

- ONE: That's what I am sorry. It's not a long has human to the same and the far you can't be considere



### Information

- Each character prediction for sentence construction was sampled using the output softmax distribution. If we simply chose the highest output, each sentence that started with the same character would be the same.
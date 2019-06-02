# Chatbot
A chatbot which answers yes/no based on a story, query &amp; an answer to the query based on the story

This chatbot is already trained on 120 epochs.
If you want to train your own model, just add 
history = model.fit([inputs_train, queries_train], answers_train,batch_size=32,epochs=120,validation_data=([inputs_test, queries_test], answers_test)) 
after the model.summary()
You can load the model and test on the loaded model

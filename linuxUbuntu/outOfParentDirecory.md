<img width="693" alt="image" src="https://user-images.githubusercontent.com/81428296/177861966-70a0a955-3011-4330-a004-579702c8b936.png">

<img width="696" alt="image" src="https://user-images.githubusercontent.com/81428296/177861918-4f721a49-961d-4b0d-86fb-e7adc13e2eec.png">


### in my example, i have nested build folder inside a build folder. we want to delete one of them, so i firstly move the inside folder to direcoty where outside folder reside, namely the home directory
<img width="598" alt="image" src="https://user-images.githubusercontent.com/81428296/177862201-9224c9b9-acf2-4d10-9e68-76e631fb420f.png">
#### then I delete the outside folder (which is not empty, since last step copy its content to targeted place)
<img width="369" alt="image" src="https://user-images.githubusercontent.com/81428296/177862479-ecbb904a-9d13-418f-977e-ce2ffeba30ac.png">
#### then i rename the new created folder to the right name
<img width="408" alt="image" src="https://user-images.githubusercontent.com/81428296/177862780-1661798b-19d1-49c6-83eb-6e9388127935.png">

### note: this case is different from the case at the top since this new created folder build2 is empty. so it can move successfully without risk of merging

### note: ~ here represents home directory, and /* represents every element under the directory
<img width="908" alt="image" src="https://user-images.githubusercontent.com/81428296/177863403-4a7117a6-8a74-4037-8de6-8725e1e9022a.png">

### note: ~ here represents home directory

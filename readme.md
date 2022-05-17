#  Prescription Pill Identification - William Glover Capstone AIM240

This capstone classifies a prescription drug using an image of the pill on top of a solid colored background. It outputs the confidence level of the classification as well. 

This is a demonstration of Artificial Intelligence and Machine learning for an academic project. This project should be used for nothing else than a demonstration and an academic project. Under no circumstances should you rely on this project to identify prescription pills you or someone else intend on using. The outputs of this project should not aid anyone in identifying prescription pills, and the results should be used as a reference value only. 

## Sample Output
![alt text](https://github.com/WillDeveloped/PrescriptionDrugClassifier/blob/main/SampleOutput.png?raw=true)

## Colab vs Notebook

I recommend running this in colab, otherwise you'll have to adjust the cv2_imshow(img) lines to be cv2.imshow('img.jpg', 'Title of Image'). There are alot of outputs, so the best bet would be to run the colab file. 

colab url: https://colab.research.google.com/drive/11r3lZHzlRFXjx_bZJoiCPpmJuB9ibAZR?usp=sharing


## How to use

All the top slides are methods used by this program. All slides should be initialized, except for the slides contained in the section 'Putting it all together'. This was done to keep code organized. 

Once all the slides are initialized, in the section titled 'Putting it all together', the second line declares an image. Change this to be the image you're trying to classify. Then click play and watch the magic. 

```bash
#This slide is a working example of the capstone in action. Right now images need to be individual. 

img = cv2.imread("CHANGE_ME_TO_YOUR_IMAGE.jpg") #Change to what ever image is being passed in
pilldata = pd.read_csv('cleanedPillboxData.csv')
cv2_imshow(img)
```

## Contributing
William Glover & 
Habib Matar

## License
[MIT](https://choosealicense.com/licenses/mit/) Feel free to use, build on, take code from. 


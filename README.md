# Citizennet React Challenge

## Your task is to display logos in a certain order, based on an input JSON array.

Modify https://github.com/zacfree/react-challenge/blob/master/src/App.js to do the following:
   - Load this JSON file https://ac.aws.citizennet.com/assets/qspreviews/qs_interview_data.json
   - Sort the names by ```audience_size```, in descending order. You will display the corresponding picture as follows:
      - Use this layout as a guideline: https://github.com/zacfree/react-challenge/blob/master/assets/demo.png
      - The largest ```audience_size``` item should be at the top left, the second largest should be to the right of that, and so on.
      - You should have at least 4 columns if there are 4 or more names in the json array.
      - Note you will also need the rounded box outline surrounding each picture.
      - You can leave the pictures as color, no need to recolor them as black and white.
      - Add a hover state with a dark, semi-transparent overlay and display the ```id``` inside ```source_items``` of the hovered name.
   - Your code should work for arbitrary organization of the json array input. We will test with a different JSON file!

How to contribute (using browser)

## Overview of updating content with browser

Open a browser and go to the main GitHub repo [cloudcomputingCurriculum](https://github.com/cloudcomputingcurricula/Cloud-Computing-Curricula)

- Click on Fork button up top
- If you are using the browser, you can start editing content right on the browser. 
    - If you prefer using a local file, you can also click on “Clone or download” button for a local copy of your fork. 
- Once you are done updating content (Please see Style Doc for formatting instructions), click on “New Pull Request” button.
- On the new page that comes up, click on “Compare across forks” link on top.
- If you have changes, you will see “Able to merge” notification and will be able to commit by clicking on ”Create pull request” button. 
    - Enter any comments necessary and click the “Create pull request” button again. 
- If there are no conflicts, you will see a button that says “Merge pull request” and click on it to submit changes. 
- At this point, you can delete your fork, by clicking on “Delete fork” button. 
- Type the following:
    - sudo git clone git://cloudcomputingcurricula/Cloud-Computing-Curricula.git
    - cd Cloud-Computing-Curricula
    - git remote add —track master cloudcomputingcurricula git://github.com/cloudcomputingcurricula git://github.com/cloudcomputingcurricula/Cloud-Computing-Curricula.git
    - sudo git fetch cloudcomputingcurricula (to synchronize)
    - sudo git merge cloudcomputingcurricula/master (to merge your local updates)

# RajLab_website
www.rajlab.org  

## The official website for the lab of Dr. Towfique Raj  
*Icahn School of Medicine at Mount Sinai  
Department of Neuroscience  
Department of Genetics & Genomic Sciences
Ronald M. Loeb Center for Alzheimer's Disease
Icahn Building, 1425 Madison Avenue  
New York, NY 10029*  

<hr>

# Updating the Website - Tutorial  
* All `code` is to be executed in the terminal/command line.
- The website uses javascript to take data CSVs and automatically construct the webpages. The following pages are currently updatable by editing the CSVs:
    + [**Publications & Presentations**](https://rajlabmssm.github.io/RajLab_website/publications.html): Currently only the Publications table is automated. Presentations must be updated by editing the HTML itself.
    + [**Funding**](https://rajlabmssm.github.io/RajLab_website/funding.html): Fully automated.
- All other pages must be updated by editing the HTML files. A good IDE is recommended to do this; I reccommend [Visual Studio Code](https://code.visualstudio.com) combined with the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer), to see how your edits change the website in real-time.
- If you want to edit the Navbar or the Footer, you only need to edit the `navbar.html` and/or `footer.html` files in order to propogate these changes to the whole website.

<br><br>

1. **Clone GitHub Repo**  
    - Go to the location on your computer where you want to copy the repo:  
    ```sh
    cd <desired_folder_location>
    ```  
    - Clone the repo (*only necessary the first time*):  
    ```sh
    git clone https://github.com/RajLabMSSM/RajLab_website.git
    ```  

2. **Edit CSV Files**  
    - In the folder `documents` you will find the following files:  
        + `publications_Raj_Lab.csv`: A table of all publications.  
        + `Raj_Grants.csv`: A table of all grants awarded.
    - Open these files in Excel, add new rows, and save the file (without changing the name or extension):
        + *Important!*: Aside from entering new rows, you must keep the exact same table structure. Do NOT edit the number or names of columns as the javascript code uses these.
3. **Push Changes to GitHub**
    - Make sure you're within the `RajLab_website` folder:
    ```sh
    cd RajLab_website
    ```  
    - Stage changes: 
    ```sh
    git add .
    ```  
    - Commit changes:  
    ```sh
    git commit -m <write_commit_message_here>
    ```  
    - Push changes to GitHub: 
    ```sh
    git push
    ```

<br>

- And voilà! Your website will now be updated, all with no or minimal HTML coding:
    + **Note**: You may have to wait a little bit for all the changes to fully appear in the website (GitHub Pages can take some time to update). 

<hr><hr>

### Web Creators:  
**Brian M. Schilder** & **Madison Parks**  
*Icahn School of Medicine at Mount Sinai  
Department of Neuroscience  
Department of Genetics & Genomic Sciences  
Ronald M. Loeb Center for Alzheimer's Disease  
Icahn Building, 1425 Madison Avenue  
New York, NY 10029*  

* Tutorial created by **Brian M. Schilder**





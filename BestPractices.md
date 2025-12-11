# Best Practices for Creating GitHub Repositories for Research Code 

## Create a README File
The README acts as a guide to the repository and is as important as the abstract. At a minimum, it should describe an overview of the research project and provide instructions on how to use the code. Use the template from this repository.

## Choose a License
Assigning a license to your repository can protect your work by telling users what they can and can’t do with your code. Open-source licenses are recommended in academia because they support open science and encourage collaboration and reuse.  

For help choosing a license, see [choosealicense.com](choosealicense.com>).   
 
Read more about [licensing a repository on GitHub](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository).  

## Organize Files and Folders
The folder structure of your repository will depend on your project and programming language, but could include the following: 
* **src/**: source code files 
* **scripts/**: scripts to run models, evaluation, etc. 
* **docs/**: documentation related to the project 
* **data/**: sample datasets or input files (avoid uploading large datasets and see data deposit for appropriate options for UWaterloo researchers) 
* **tests/**: unit or integration tests 

The following files should be in the root directory (top-level): 
* README.md 
* LICENSE 
* CITATION.cff 
* .gitignore 

See also guidance on [file naming](http://subjectguides.uwaterloo.ca/rdm/basics#filenaming). 

### Example repository structure
GitHub repository/  
├── docs/  
├── data/  
├── scripts/  
├── src/  
├── tests/  
├── .gitignore  
├── README.md  
├── CITATION.cff  
└── LICENSE 

## Preserve the Repository
While GitHub is a popular public platform for hosting code, the University of Waterloo Libraries recommends that researchers also archive research code on repositories that issue a Persistent Identifier (PID).  

See [data deposit](https://subjectguides.uwaterloo.ca/rdm/datadeposit) to find repositories. 

## Add a CITATION File
Add a citation file to the GitHub repository to indicate how the software should be cited for users. Include the PID (e.g., DOI) assigned by the archiving repository. 

See example [CITATION.cff](https://github.com/a2roussy/UWaterlooRDM-template/blob/main/CITATION.cff) in repository.

Learn more:
* [About CITATION files - GitHub Docs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files) 
* [Referencing and citing content - GitHub Docs](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)

## Other Recommendations
### Large files and storage
* Keep your repository compact (ideally <1GB if possible). See [Managing large files - GitHub Docs](https://docs.github.com/en/repositories/working-with-files/managing-large-files).  
* Avoid depositing large datasets. See [data deposit](https://subjectguides.uwaterloo.ca/rdm/datadeposit) options for UWaterloo researchers.

### Documentation
* Include code comments/in-code documentation. See [Best practices for writing code comments - Stack Overflow](https://stackoverflow.blog/2021/12/23/best-practices-for-writing-code-comments/). 
* Use notebooks (e.g., Jupyter Notebooks, Google Collab). 
* Consult the [style guide](https://google.github.io/styleguide/) for the programming language you are using.

## Additional Resources
* [Best practices for repositories - GitHub Docs](https://docs.github.com/en/repositories/creating-and-managing-repositories/best-practices-for-repositories)
* [Guide for Reproducible Research - The Turing Way](https://book.the-turing-way.org/reproducible-research/reproducible-research/)
* [The Good Research Code Handbook - Good research code](https://goodresearch.dev/)
* [FAIR Software](https://fair-software.eu/)

## References
* [File Structure: Broad Institute of MIT and Harvard](https://mitcommlab.mit.edu/broad/commkit/file-structure/)
* [The Good Research Code Handbook - Good research code](https://goodresearch.dev/)
* [Sharing your code - Using Git to Code, Collaborate and Share](https://imperialcollegelondon.github.io/grad_school_git_course/l2-01-sharing_your_code/index.html)

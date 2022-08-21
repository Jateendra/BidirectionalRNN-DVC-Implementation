# DVC Project for NLP BiLSTM

## 1 . Clone
  - Clone from https://github.com/c17hawke/DVC-project-Docs-template-v2.0 
	- Click on "Use Template"
	- Give Project Name as : "BidirectionalRNN-DVC-Implementation"
	- Include all branches 
	- Create Repository
	
## 2 . Open VS Code :
	- git clone https://github.com/Jateendra/BidirectionalRNN-DVC-Implementation.git
	- cd BidirectionalRNN-DVC-Implementation
	
*** . Which folder does what ?
	 - .github\workflows : After commiting the code helps to do CICD pipeline .
   
	 - artifacts : stores the intermediate data , transformed.
   
	 - configs : configurations , where are the files present etc .
   
	 - docs : Documentation related to the project .
   
	 - logs : logs
   
	 - src : Contains all our code base .
   
			- __init__.py : logs code
      
			- components : Training , Preprocessing , Evaluation Components .
      
			- constants : Supplying common constants across the package or projects .
      
			- pipeline : stage files . Stage01 , ... , Stage02 .
      
			- template : Stage template files .
      
			- utils : common operations we do everytime . Ex : Creating directory , reading yaml files , 
      
	 - .gitignore : Some files which we don't want to commit into github .
   
	 - dvc.yaml : helps to run files in stages .
   
	 - init_setup.sh : Helps to run basic setup . Ex : Creating the environment , install the requirements .
   
	 - LICENSE : licenses
   
	 - mkdocs.yml : helps to arrange the files of documentation .
   
	 - params.yaml : to write parameters , training parameters . Ex : epochs , batch_size /
   
	 - README.md : custom documentation 
   
	 - requirements.txt : library and packages 
   
	 - setup.py : Helps to keep src as a package .
   
	 
*** Use gitbash terminal always .	 
	 
## 3 . Write your codes into params.yaml , requirements.txt , setup.py files . 

		- ** Ref : https://drive.google.com/drive/u/0/folders/1JzIOTdE76CWWxuq-EkLppKZXmofl_h6I  , biRNN_demo.ipynb
		- ** Ref : https://github.com/c17hawke/DLCVNLP-biRNN/blob/main/setup.py
		- bash init_setup.sh

## 4 . Commit the changes :

	- Go to Source Control -> write commit comment as "first commit" -> Ctrl+Enter
	
## 5 . conda activate ./env

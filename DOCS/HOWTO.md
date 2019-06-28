**Join us !**

If you are already a member of the University of Pisa, you should:

1. join the [organization](https://github.com/orgs/Unipisa) on github

2. join the [Software Heritage team](https://github.com/orgs/Unipisa/teams/software-heritage)

If you are not, you should contact the administrators (@Unipisa/swhap-pisa-administrators) in order to be invited as an external collaborator. This will allow you to cooperate with our team after creating your own repository.

**Then**

1. Please read carefully the [documentation](THE_PROCESS.md) about the acquisition process. Furthermore, you should take a look to the format for [actors](https://github.com/Unipisa/SWHAP-TEMPLATE/blob/master/DEPOSITORY/ACTORS.md), [journal](https://github.com/Unipisa/SWHAP-TEMPLATE/blob/master/DEPOSITORY/JOURNAL.md) and [catalogue](https://github.com/Unipisa/SWHAP-TEMPLATE/blob/master/DEPOSITORY/CATALOGUE.md) in the [SWHAP-TEMPLATE depository](https://github.com/Unipisa/SWHAP-TEMPLATE/tree/master/DEPOSITORY).
2. Instantiate the process:
  * descrivere il processo di istanziazione nel dettaglio


**Instantiate the Workbench from [SWHAP-TEMPLATE](https://github.com/Unipisa/SWHAP-TEMPLATE) via GitHub.com**

Make a new repository SWHAP-TEMPLATE (see the following figure)

   1. go to [DIUNIPI-SWH-TEMPLATE](https://github.com/Unipisa/SWHAP-TEMPLATE) and click on ["Use this template"](https://github.com/Unipisa/SWHAP-TEMPLATE/generate)

![create LAB repository from template](./IMAGES/template_repository_lab-1.png)

   2. fill the name with SWG-$SW_NAME-LAB and the description as in figure

![create LAB repository from template](./IMAGES/template_repository_lab-2.png)

   3. You got a new repository with the file and directory structure of [DIUNIPI-SWH-TEMPLATE](https://github.com/Unipisa/SWHAP-TEMPLATE)

![create LAB repository from template](./IMAGES/template_repository_lab-3.png)



then on terminal

~~~
$ mkdir SWH-$SW_NAME-LAB
$ cd SWH-$SW_NAME-LAB
$ git init
$ git remote add origin https://github.com/Unipisa/SWH-$SW_NAME-LAB.git
$ git push -u origin master
~~~

**Fill the DEPOSITORY**

**Finalize and archive the DEPOSITORY**

~~~
$ git clone SWH-$SW_NAME-LAB.git
$ cd SWH-$SW+NAME-LAB
$ git filter-branch --prune-empty --subdirectory-filter DEPOSITORY master
> creare repository SWH-$SW_NAME-DEPOSITORY
> git set-url origin SWH-$SW_NAME-DEPOSITORY.git
> aggiornare journal con data chiusure repository
> achiviare repository e settarlo pubblico
$ cd ..
$ cd SWH-$SW_NAME-LAB
$ cp DEPOSITORY/ACTORS.md WORKBENCH_TEMPLATE   
$ cp -r DEPOSITORY/SOURCE WORKBENCH_TEMPLATE/  
$ rm -R DEPOSITORY
~~~

Then, [archive](<https://help.github.com/en/articles/archiving-repositories>) the depository repository (under repository settings, in the Danger Zone).

![archive](./IMAGES/archive_repository.png)

and write into SWHAP@PISA JOURNAL.md or notify @Unipisa/swhap-pisa-administrators  

**Create the synthetic Git**

todo

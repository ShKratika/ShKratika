Action Items
• Create a local git repository and move the entire code base to it
• Create a new branch for a new feature you want to add to the application
• Merge back the created branch with the master branch
• Create a remote repository
• Push the local repository to company’s remote repository

Steps performed:

Remote repo created: https://github.com/ShKratika/ShKratika
Master branch has sample-project code shared by Edureka in PDF - https://backup-edureka.s3.ap-south-1.amazonaws.com/sample-project.zip
C:\Users\ksharm16\Documents\Edureka\GitAsgnmnt\CodeBase is where master code was checked-out
WorkingDir is the branch cut from master branch : https://github.com/ShKratika/ShKratika/tree/WorkingDir
Added NewBranchTest.txt file in WorkingDir and merged with master

MINGW64 ~/Documents/Edureka/GitAsgnmnt/EduWorkspace/ShKratika (WorkingDir)
$ git log
commit 7b37f71d31fdb7f9eb4fa6373d0884ffd75e85da
Author: Sharma <kratika_sharma@optum.com>
Date:   Tue Dec 14 21:55:39 2021 +0530

    Changes done in new release branch

commit c3e368d407d6cdac8450f99229657bec4b119249
Author: Sharma <kratika_sharma@optum.com>
Date:   Tue Dec 14 21:50:36 2021 +0530

    Workingdir changes

commit e6080338ed655901c8637440ce9db976ead79945
Author: Sharma <kratika_sharma@optum.com>
Date:   Tue Dec 14 21:39:09 2021 +0530

    Sample code pushed to remote

commit 8759e999c7ff0a0f4d5bd015728590716f4248df
Author: Sharma <kratika_sharma@optum.com>
Date:   Tue Dec 14 20:22:14 2021 +0530

    Initial file
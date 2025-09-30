---
content_type: page
description: This section provides information about the lab assignments, class machines,
  and aids for working in labs.
hide_download: true
hide_download_original: null
learning_resource_types:
- Laboratory Assignments
ocw_type: CourseSection
title: Labs
uid: c6bbff67-7478-f7d2-6053-2d402c0b0bf7
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Laboratory Assignments
----------------------

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
LABS
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
SUPPORTING FILES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
Getting started ({{% resource_link a5ba851a-a5a2-14dd-fa9b-b2f1ee378113 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
Lock server ({{% resource_link 249a3c22-4b01-f254-7ee2-5a3971ce2a73 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
lab-1.zip ({{% resource_link 87a3ee7e-b7ad-73ad-cfe7-49e3b5f749dd "ZIP" %}}) (The ZIP file contains: 5 .c files, 2 .h files, 1 Makefile, and 1 .x file.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
Basic file server ({{% resource_link 67387d70-5672-a2c8-3be3-3c8b2f595db4 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
lab-2.zip ({{% resource_link 291a435c-6e83-60dc-bf9f-cc312ae558f8 "ZIP" %}}) (The ZIP file contains: 5 .c files, 3 .h files, 2 .x files, 1 .pl file, and 1 Makefile.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
File server: Reading, writing, and sharing files ({{% resource_link 66657c51-906f-8ac1-8d9b-7786004253e4 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
lab-3.zip ({{% resource_link 984cb68e-2870-9677-fe20-14e1ebabb999 "ZIP" %}}) (The ZIP file contains: test-lab-3.pl.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
MKDIR, REMOVE, and locking ({{% resource_link 815ab2a0-8125-3925-0d25-5b084e07ab7e "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
lab-4.zip ({{% resource_link ed34f3f6-395c-d377-ec14-a9123c7fc50d "ZIP" %}}) (The ZIP file contains: 6 .c files, 3 .h files, 2 .x files, 1 Makefile, and 1 .pl file.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
Cache consistency ({{% resource_link b55ec784-a521-d8ca-4e2f-97a086b68972 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Class Machines
--------------

We have multiple machines so that you can test your networking code on multiple hosts. As the term progresses, we may add additional machines as needed.

Aids for Working on Labs
------------------------

There are a number of resources available to help you with the lab portion of this course:

*   We have compiled some basic information about logging into our systems and tools for developing C++ programs. This is available in the Getting Started file.  
      
     
*   **The SFS source code**: All the labs use the RPC, asynchronous I/O, and utility libraries that come with the SFS source code. You may need to browse the SFS source to figure out how it works. It's available on the class machines or at the SFS project page. You may also find the SFS and file system tookit papers useful:

Mazières, David, Michael Kaminsky, M. Frans Kaashoek, and Emmett Witchel. "Separating Key Management From File System Security." _Operating Systems Review_ 34, no. 5 (December 1999): 124-139.

Mazières, David. "A Toolkit for User-level File Systems." Proceedings of the USENIX Technical Conference (June 2001): 261-274.

*   **FreeBSD Architecture**: You can find a good summary of how FreeBSD works in an appendix to the Operating Systems Concepts book by Silberschatz, Galvin, and Gagne. Click on The FreeBSD System link on the following [Web site](http://codex.cs.yale.edu/avi/os-book/). FreeBSD is the UNIX® variant running on the 6.824 machines.)  
      
     
*   **UNIX® network programming**: W. Richard Stevens' books "UNIX® Network Programming'" Volume 1 and 2 are classic references for network programming. If you are struggling with the sockets interface it could be a helpful purchase. See the useful book list in the syllabus for other helpful references.  
      
     
*   **Core files**: When/if your program crashes it will leave a core file behind (named something.core). Examining core files with gdb is a valuable way to learn what went wrong. To get started with gdb type: "gdb program program.core" and then type the gdb command "bt". GDB will return a trace showing exactly where the program crashed. GDB offers many more features. Check out [the GDB manual](http://www.gnu.org/software/gdb/documentation/) for full documentation.
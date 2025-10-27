



two threads share  the  same  address  space
 COntext   Switchoing  between  threads is usally  less  expensive  than  between  process
   the  cost  of  communication  between  threads  is relatively

     why  multthreading ?
     ->  In single   thrrraded  environment,  olny   one task  ay  a time  can performed.
       CPu   cycles  are  wasted  ,  for example   when    waiting  for  user  input
         MUltitasking  allows    idle  cpu  time to  be  put    to good
  . Athread  is an indepedent   sdquential   path  of  execution  within  program
    main thread   si  creted  autimatically
     instruction  run sequentially
       many   threads in an  program  exists  in an common     memory  space  and can   therefore  share     both data  and  code(i.e)  they are  lightweight  compared  tom process.
       same    threads  same resources
         #3 Important   Concepts  to  muthreading
          !  Xreating   threads   and  provding   the code   that  gets   ex3cuted  by  a thread
            Accessing   common   data  and  code  through  syynchonizztion
             Transitioning  between    thread  and states.

               The Main  Thread
               .When  a standalone   spplication  is  run   a user  thread  is created   to  execute    the main  method  of  application
                is called the main   thread.
                  If  no another    user thread  are spawned,  the  programmers terminate   the main  method   finishes  executing.
                  \  all other    threads,  called   child    are  spawned  from the  main  thread.
                    The main   method  can  then finish, but  the program  will keep  running  until  all users  threads   have  completred
                       The  runtime   environment  distinguishes  between     user threads   and  daemon threads=
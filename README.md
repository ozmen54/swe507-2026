# SWE 507 PARALLEL COMPUTING

Please click the link below to see the projects: <br> 

## Projects:

<table>
  <header>
    <th>No</th>
    <th>Project Title</th>
    <th>Tasks</th>
    <th>Due Date</th>
    <th>Other</th>
  </header>
  <body>
    <tr>
      <td>1</td>
      <td><b>Multi-thread parallel programming on multi-core CPU.</b></td>
      <td> 
        <b>a)</b> Do sequential computation, take timestamps as shown in the class. Repeat experiment 5 times. Take average execution time.<br> 
        <b>b)</b> Do the same computation with 3, 9 and 12 threads.  <br> 
        <b>c)</b> Repeat experiments 5 times, and take the average execution time. <br> 
        <b>d)</b> Comment on execution times and speedup achieved using multiple threads. 
      </td>
      <td>25 Feb 2026 in class</td>
      <td><a href="pro1.pdf">Project1</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td><b>Process based parallel computing using shared memory.</b></td>
      <td>
        <b>a)</b> Do the experiments 1, 3, 6 processes on your local computer. <br> 
        <b>b)</b> Check the correctnes and measure the performance.<br>
        <b>c)</b> Compare the performance with thread approach. <br> 
      </td>
      <td>18 Mar 2026 in class</td>
      <td><a href="pro2.pdf">Project2</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td><b>Distributed parallel computing with MPI + Shared memory using Pthread</b></td>
      <td>
        <b>a)</b> Create an MPI cluster with three nodes on cloud (AWS or Azure). <br> 
        <b>b)</b> Run your algorthm in sequential mode on a node (ec2 instance), take the timestamps as shown in the class. <br> 
        <b>c)</b> Do the computation with 3 MPI workers, 2 Pthreads on each worker (see project description). <br> 
        <b>d)</b> Measure the performance.<br> 
        <b>e)</b> Discuss the results. 
      </td>
      <td>15 April 2026 in class</td>
      <td><a href="pro3.pdf">Project3</a></td>
    </tr>
     <tr>
      <td>4</td>
      <td><b>Parallel image processing application on GPU</b></td>
      <td>
        <b>a)</b> Implement a vector parallel solution to the problem using Cuda. <br>
        <b>b)</b> Measure the performance of your implementation. <br>
        <b>c)</b> Compare the performance of your implementation with the serial one.  <br>
        <b>d)</b> Discuss parallelization of your solution.  
      </td>
      <td>6 May 2026 in class</td>
      <td><a href="pro4.pdf">Project4</a></td>
    </tr>
     <tr>
      <td>5</td>
      <td><b>Distributed parallel computing with Apache-Hadoop. </b></td>
      <td>
        <b>a)</b> Install Apache-Hadoop and HDFS as single node cluster on your computer. <br>
        <b>b)</b> Implement a Java solution to the same problem of the previous image processing problem. <br>
        <b>c)</b> Obtain the Jar file and move it under HDFS. <br>
        <b>d)</b> Show that your solution work using Hadoop Map-Reduce approach. <br>
        <b>e)</b> Discuss about pros and cons of this approach. Check out Apache-Spark.
      </td>
      <td>20 May 2026 in class<br>(Last week)</td>
      <td><a href="pro5.pdf">Project5</a></td>
    </tr>

  </body>
</table>


## General rules for project grading:
* Each students are allowed 10 minutes to present their work.
* Students are called to present their work based on a random number announced in the class. 
* Members (and groups) who are not contributed at all, and do not show up at presentation will get 0 (zero) grade.


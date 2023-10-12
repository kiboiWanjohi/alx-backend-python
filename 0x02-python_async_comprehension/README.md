<div class="col-xs-12 col-md-10 col-lg-8 contains-images">

      <h1 class="gap">0x02. Python - Async Comprehension</h1>

  <div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:19,&quot;value&quot;:&quot;Python&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;},{&quot;id&quot;:35,&quot;value&quot;:&quot;Back-end&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"><div class="align-items-center d-flex flex-wrap gap-3 my-2"><span class="label label-primary" style="font-size: 14px;">Python</span><span class="label label-primary" style="font-size: 14px;">Back-end</span></div></div>

  <div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Emmanuel Turlay, Staff Software Engineer at Cruise&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:false,&quot;auto_correction_available_at&quot;:&quot;2023-10-10T00:00:00.000+03:00&quot;,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:true,&quot;started&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2023-10-09T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2023-10-12T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2023-10-15T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"><ul class="list-group metadata" id="project-metadata"><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-user fa-fw"></i> By: Emmanuel Turlay, Staff Software Engineer at Cruise</li><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-gear fa-fw"></i> Weight: 1</li><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-calendar fa-fw"></i> Project will start <span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2023-10-09 06:00 (GMT+03:00)"><span class="datetime">Oct 9, 2023 6:00 AM</span></span>, must end by <span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2023-10-12 06:00 (GMT+03:00)"><span class="datetime">Oct 12, 2023 6:00 AM</span></span></li><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-check fa-fw"></i> Checker will be released at <span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2023-10-10 00:00 (GMT+03:00)"><span class="datetime">Oct 10, 2023 12:00 AM</span></span></li><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-square-check fa-fw"></i> An auto review will be launched at the deadline</li></ul></div>




    


    <div id="project_id" style="display: none" data-project-id="1231"></div>



      

      

      <div class="panel panel-default" id="project-description">
  <div class="panel-body">
    <p><img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/12/ee85b9f67c384e29525b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231009%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20231009T125407Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=a213c85dd0b40789d61e2fad3f27717bb9a74c2be27aa7e58bba68abe2548e6b" alt="" loading="lazy" style=""></p>

<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/hlwtED-iLsdORSgly8DsyQ" title="PEP 530 -- Asynchronous Comprehensions" target="_blank">PEP 530 – Asynchronous Comprehensions</a></li>
<li><a href="/rltoken/0OkbObYzCKtO7ZUAxfKvkw" title="What’s New in Python: Asynchronous Comprehensions / Generators" target="_blank">What’s New in Python: Asynchronous Comprehensions / Generators</a></li>
<li><a href="/rltoken/l4Fnno568VbVIn9GvrFVtQ" title="Type-hints for generators" target="_blank">Type-hints for generators</a></li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/_jK22HqiCeh5NjKJ4ZHBww" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<ul>
<li>How to write an asynchronous generator</li>
<li>How to use async comprehensions</li>
<li>How to type-annotate generators</li>
</ul>

<h2>Requirements</h2>

<h3>General</h3>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code></li>
<li>All your files will be interpreted/compiled on Ubuntu 18.04 LTS using <code>python3</code> (version 3.7)</li>
<li>All your files should end with a new line</li>
<li>The first line of all your files should be exactly <code>#!/usr/bin/env python3</code></li>
<li>A <code>README.md</code> file, at the root of the folder of the project, is mandatory</li>
<li>Your code should use the <code>pycodestyle</code> style (version 2.5.x)</li>
<li>The length of your files will be tested using <code>wc</code></li>
<li>All your modules should have a documentation (<code>python3 -c 'print(__import__("my_module").__doc__)'</code>)</li>
<li>All your functions should have a documentation (<code>python3 -c 'print(__import__("my_module").my_function.__doc__)'</code></li>
<li>A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)</li>
<li>All your functions and coroutines must be type-annotated.</li>
</ul>

  </div>
</div>


      

      

        
          <h2 class="gap">Tasks</h2>

    <div data-role="task11630" data-position="1" id="task-num-0">
      <div class="panel panel-default task-card " id="task-11630">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      0. Async Generator
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Write a coroutine called <code>async_generator</code> that takes no arguments. </p>

<p>The coroutine will loop 10 times, each time asynchronously wait 1 second, then yield a random number between 0 and 10. Use the <code>random</code> module. </p>

<pre><code>bob@dylan:~$ cat 0-main.py
#!/usr/bin/env python3

import asyncio

async_generator = __import__('0-async_generator').async_generator

async def print_yielded_values():
    result = []
    async for i in async_generator():
        result.append(i)
    print(result)

asyncio.run(print_yielded_values())

bob@dylan:~$ ./0-main.py
[4.403136952967102, 6.9092712604587465, 6.293445466782645, 4.549663490048418, 4.1326571686139015, 9.99058525304903, 6.726734105473811, 9.84331704602206, 1.0067279479988345, 1.3783306401737838]
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x02-python_async_comprehension</code></li>
            <li>File: <code>0-async_generator.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11630">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11630" data-batch-id="62" data-toggle="modal" data-target="#task-11630-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11630-users-done-modal" data-task-id="11630" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "0. Async Generator"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>




    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11630}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11631" data-position="2" id="task-num-1">
      <div class="panel panel-default task-card " id="task-11631">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      1. Async Comprehensions
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Import <code>async_generator</code> from the previous task and then write a coroutine called <code>async_comprehension</code> that takes no arguments. </p>

<p>The coroutine will collect 10 random numbers using an async comprehensing over <code>async_generator</code>, then return the 10 random numbers.</p>

<pre><code>bob@dylan:~$ cat 1-main.py
#!/usr/bin/env python3

import asyncio

async_comprehension = __import__('1-async_comprehension').async_comprehension


async def main():
    print(await async_comprehension())

asyncio.run(main())

bob@dylan:~$ ./1-main.py
[9.861842105071727, 8.572355293354995, 1.7467182056248265, 4.0724372912858575, 0.5524750922145316, 8.084266576021555, 8.387128918690468, 1.5486451376520916, 7.713335177885325, 7.673533267041574]

</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x02-python_async_comprehension</code></li>
            <li>File: <code>1-async_comprehension.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11631">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11631" data-batch-id="62" data-toggle="modal" data-target="#task-11631-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11631-users-done-modal" data-task-id="11631" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "1. Async Comprehensions"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>




    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11631}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11632" data-position="3" id="task-num-2">
      <div class="panel panel-default task-card " id="task-11632">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      2. Run time for four parallel comprehensions
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Import <code>async_comprehension</code> from the previous file and write a <code>measure_runtime</code> coroutine that will execute <code>async_comprehension</code> four times in parallel using <code>asyncio.gather</code>.</p>

<p><code>measure_runtime</code> should measure the total runtime and return it.</p>

<p>Notice that the total runtime is roughly 10 seconds, explain it to yourself.</p>

<pre><code>bob@dylan:~$ cat 2-main.py
#!/usr/bin/env python3

import asyncio


measure_runtime = __import__('2-measure_runtime').measure_runtime


async def main():
    return await(measure_runtime())

print(
    asyncio.run(main())
)

bob@dylan:~$ ./2-main.py
10.021936893463135

</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x02-python_async_comprehension</code></li>
            <li>File: <code>2-measure_runtime.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11632">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11632" data-batch-id="62" data-toggle="modal" data-target="#task-11632-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11632-users-done-modal" data-task-id="11632" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "2. Run time for four parallel comprehensions"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>




    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11632}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>





          <div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;available&quot;:true,&quot;description&quot;:&quot;\u003cp\u003eUbuntu 18.04 with Python 3.7\u003c/p\u003e\n&quot;,&quot;id&quot;:23,&quot;name&quot;:&quot;Ubuntu 18.04 - Python 3.7&quot;,&quot;online&quot;:true}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;tDIaxOsCsITHzOIHWoEygpcKcQdjfYTH2KC1-TMrVhgk4Nh30Qsdnjda32cztIShRJ5ePVUxuLTdfd-FDJTlHA&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"><div><div class="d-flex gap-4 sandboxes-filters"><a class="btn btn-outline-primary"><i aria-hidden="true" class="fa-solid fa-filter"></i><span class="ml-2">Running only</span></a><div class="align-items-center d-flex" style="position: relative; width: 100%;"><input class="form-control" placeholder="Search for an image ..." type="search" value=""></div></div><div class="mt-3"><h3>1 image<small class="ml-2">(0/2 Sandboxes spawned)</small></h3></div><div class="mt-3"><div class="panel panel-default"><div class="panel-body"><div class="align-items-center d-flex flex-wrap justify-content-between"><div><h3 class="mt-0"><i aria-hidden="true" class="fa-solid fa-terminal text-danger"></i><span class="ml-2">Ubuntu 18.04 - Python 3.7</span></h3><div class="mt-2 text-muted"><p>Ubuntu 18.04 with Python 3.7</p>
</div></div><div class="d-flex flex-wrap gap-5"><a class="btn btn-success"><i aria-hidden="true" class="fa-solid fa-play"></i><span class="ml-2">Run</span></a></div></div></div></div></div></div></div></div></div></div></div>

  </div>

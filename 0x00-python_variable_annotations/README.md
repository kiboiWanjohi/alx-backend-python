<div class="project row">
  <div class="col-xs-12 col-md-10 col-lg-8 contains-images">

      <h1 class="gap">0x00. Python - Variable Annotations</h1>

  <div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:19,&quot;value&quot;:&quot;Python&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;},{&quot;id&quot;:35,&quot;value&quot;:&quot;Back-end&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"><div class="align-items-center d-flex flex-wrap gap-3 my-2"><span class="label label-primary" style="font-size: 14px;">Python</span><span class="label label-primary" style="font-size: 14px;">Back-end</span></div></div>

  <div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Emmanuel Turlay, Staff Software Engineer at Cruise&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;auto_correction_available_at&quot;:&quot;2023-10-05T12:00:00.000+03:00&quot;,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:true,&quot;started&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2023-10-05T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2023-10-06T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2023-10-07T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"><ul class="list-group metadata" id="project-metadata"><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-user fa-fw"></i> By: Emmanuel Turlay, Staff Software Engineer at Cruise</li><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-gear fa-fw"></i> Weight: 1</li><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-calendar fa-fw"></i> Project will start <span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2023-10-05 06:00 (GMT+03:00)"><span class="datetime">Oct 5, 2023 6:00 AM</span></span>, must end by <span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2023-10-06 06:00 (GMT+03:00)"><span class="datetime">Oct 6, 2023 6:00 AM</span></span></li><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-check fa-fw"></i> Checker was released at <span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2023-10-05 12:00 (GMT+03:00)"><span class="datetime">Oct 5, 2023 12:00 PM</span></span></li><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-square-check fa-fw"></i> An auto review will be launched at the deadline</li></ul></div>




    


    <div id="project_id" style="display: none" data-project-id="1229"></div>



      

        <div class="panel panel-default">
    <div class="panel-heading">
      <h3 class="panel-title">Concepts</h3>
    </div>
    <div class="panel-body">
      <p>
        <em>For this project, we expect you to look at this concept:</em>
      </p>

      <ul>
          <li>
            <a href="/concepts/554">Advanced Python</a>
          </li>
      </ul>
    </div>
  </div>


      <div class="panel panel-default" id="project-description">
  <div class="panel-body">
    <p><img src="https://i.redd.it/y9y25tefi5401.png" alt="" loading="lazy" style=""></p>

<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/5j0OtdWh36_HVAHKJX2gaA" title="Python 3 typing documentation" target="_blank">Python 3 typing documentation</a></li>
<li><a href="/rltoken/Eud-nrUG7x3iT6JD2Sas-g" title="MyPy cheat sheet" target="_blank">MyPy cheat sheet</a></li>
</ul>

<h2>Learning Objectives</h2>

<h3>General</h3>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/hGUom4nCewYmroS4ii_ZDQ" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<ul>
<li>Type annotations in Python 3</li>
<li>How you can use type annotations to specify function signatures and variable types</li>
<li>Duck typing</li>
<li>How to validate your code with <code>mypy</code></li>
</ul>

<h2>Requirements</h2>

<h3>General</h3>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code></li>
<li>All your files will be interpreted/compiled on Ubuntu 18.04 LTS using <code>python3</code> (version 3.7)</li>
<li>All your files should end with a new line</li>
<li>The first line of all your files should be exactly <code>#!/usr/bin/env python3</code></li>
<li>A <code>README.md</code> file, at the root of the folder of the project, is mandatory</li>
<li>Your code should use the <code>pycodestyle</code> style (version 2.5.)</li>
<li>All your files must be executable</li>
<li>The length of your files will be tested using <code>wc</code></li>
<li>All your modules should have a documentation (<code>python3 -c 'print(__import__("my_module").__doc__)'</code>)</li>
<li>All your classes should have a documentation (<code>python3 -c 'print(__import__("my_module").MyClass.__doc__)'</code>)</li>
<li>All your functions (inside and outside a class) should have a documentation (<code>python3 -c 'print(__import__("my_module").my_function.__doc__)'</code> and <code>python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'</code>)</li>
<li>A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)</li>
</ul>

  </div>
</div>


      

      

        
          <h2 class="gap">Tasks</h2>

    <div data-role="task11612" data-position="1" id="task-num-0">
      <div class="panel panel-default task-card " id="task-11612">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      0. Basic annotations - add
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
    <p>Write a type-annotated function <code>add</code> that takes a float <code>a</code> and a float <code>b</code> as arguments and returns their sum as a float. </p>

<pre><code>bob@dylan:~$ cat 0-main.py
#!/usr/bin/env python3
add = __import__('0-add').add

print(add(1.11, 2.22) == 1.11 + 2.22)
print(add.__annotations__)

bob@dylan:~$ ./0-main.py
True
{'a':  &lt;class 'float'&gt;, 'b': &lt;class 'float'&gt;, 'return': &lt;class 'float'&gt;}
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x00-python_variable_annotations</code></li>
            <li>File: <code>0-add.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11612">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11612" data-batch-id="62" data-toggle="modal" data-target="#task-11612-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11612-users-done-modal" data-task-id="11612" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "0. Basic annotations - add"</h4>
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


      <button class="btn btn-default btn-sm check-your-task-11612-modal-button" data-task-id="11612" data-toggle="modal" data-target="#task-test-correction-11612-correction-modal" id="task-num-0-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11612}">
          Check your code
      </button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-11612-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">Correction of "0. Basic annotations - add"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="11612">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>
                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="11612">
        <i aria-hidden="true" class="fa-solid fa-circle-info "></i>
    </button>
    <div class="help-container" data-task-id="11612">
        <div class="check-line">
            <div class="check-inline requirement success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div>
    </div>
</div>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11612}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11613" data-position="2" id="task-num-1">
      <div class="panel panel-default task-card " id="task-11613">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      1. Basic annotations - concat
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
    <p>Write a type-annotated function <code>concat</code> that takes a string <code>str1</code> and a string <code>str2</code> as arguments and returns a concatenated string</p>

<pre><code>bob@dylan:~$ cat 1-main.py
#!/usr/bin/env python3
concat = __import__('1-concat').concat

str1 = "egg"
str2 = "shell"

print(concat(str1, str2) == "{}{}".format(str1, str2))
print(concat.__annotations__)

bob@dylan:~$ ./1-main.py
True
{'str1': &lt;class 'str'&gt;, 'str2': &lt;class 'str'&gt;, 'return': &lt;class 'str'&gt;}
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x00-python_variable_annotations</code></li>
            <li>File: <code>1-concat.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11613">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11613" data-batch-id="62" data-toggle="modal" data-target="#task-11613-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11613-users-done-modal" data-task-id="11613" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "1. Basic annotations - concat"</h4>
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


      <button class="btn btn-default btn-sm check-your-task-11613-modal-button" data-task-id="11613" data-toggle="modal" data-target="#task-test-correction-11613-correction-modal" id="task-num-1-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11613}">
          Check your code
      </button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-11613-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">Correction of "1. Basic annotations - concat"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="11613">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>
                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="11613">
        <i aria-hidden="true" class="fa-solid fa-circle-info "></i>
    </button>
    <div class="help-container" data-task-id="11613">
        <div class="check-line">
            <div class="check-inline requirement success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div>
    </div>
</div>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11613}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11614" data-position="3" id="task-num-2">
      <div class="panel panel-default task-card " id="task-11614">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      2. Basic annotations - floor
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
    <p>Write a type-annotated function <code>floor</code> which takes a float <code>n</code> as argument and returns the floor of the float.</p>

<pre><code>bob@dylan:~$ cat 2-main.py
#!/usr/bin/env python3

import math

floor = __import__('2-floor').floor

ans = floor(3.14)

print(ans == math.floor(3.14))
print(floor.__annotations__)
print("floor(3.14) returns {}, which is a {}".format(ans, type(ans)))

bob@dylan:~$ ./2-main.py
True
{'n': &lt;class 'float'&gt;, 'return': &lt;class 'int'&gt;}
floor(3.14) returns 3, which is a &lt;class 'int'&gt;
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x00-python_variable_annotations</code></li>
            <li>File: <code>2-floor.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11614">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11614" data-batch-id="62" data-toggle="modal" data-target="#task-11614-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11614-users-done-modal" data-task-id="11614" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "2. Basic annotations - floor"</h4>
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


      <button class="btn btn-default btn-sm check-your-task-11614-modal-button" data-task-id="11614" data-toggle="modal" data-target="#task-test-correction-11614-correction-modal" id="task-num-2-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11614}">
          Check your code
      </button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-11614-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">Correction of "2. Basic annotations - floor"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="11614">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>
                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="11614">
        <i aria-hidden="true" class="fa-solid fa-circle-info "></i>
    </button>
    <div class="help-container" data-task-id="11614">
        <div class="check-line">
            <div class="check-inline requirement success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div>
    </div>
</div>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11614}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11615" data-position="4" id="task-num-3">
      <div class="panel panel-default task-card " id="task-11615">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      3. Basic annotations - to string
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
    <p>Write a type-annotated function <code>to_str</code> that takes a float <code>n</code> as argument and returns the string representation of the float.</p>

<pre><code>bob@dylan:~$ cat 3-main.py
#!/usr/bin/env python3
to_str = __import__('3-to_str').to_str

pi_str = to_str(3.14)
print(pi_str == str(3.14))
print(to_str.__annotations__)
print("to_str(3.14) returns {} which is a {}".format(pi_str, type(pi_str)))

bob@dylan:~$ ./3-main.py
True
{'n': &lt;class 'float'&gt;, 'return': &lt;class 'str'&gt;}
to_str(3.14) returns 3.14, which is a &lt;class 'str'&gt;
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x00-python_variable_annotations</code></li>
            <li>File: <code>3-to_str.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11615">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11615" data-batch-id="62" data-toggle="modal" data-target="#task-11615-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11615-users-done-modal" data-task-id="11615" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "3. Basic annotations - to string"</h4>
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


      <button class="btn btn-default btn-sm check-your-task-11615-modal-button" data-task-id="11615" data-toggle="modal" data-target="#task-test-correction-11615-correction-modal" id="task-num-3-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11615}">
          Check your code
      </button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-11615-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">Correction of "3. Basic annotations - to string"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="11615">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>
                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="11615">
        <i aria-hidden="true" class="fa-solid fa-circle-info "></i>
    </button>
    <div class="help-container" data-task-id="11615">
        <div class="check-line">
            <div class="check-inline requirement success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div>
    </div>
</div>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11615}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11616" data-position="5" id="task-num-4">
      <div class="panel panel-default task-card " id="task-11616">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      4. Define variables
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
    <p>Define and annotate the following variables with the specified values:</p>

<ul>
<li><code>a</code>, an integer with a value of 1</li>
<li><code>pi</code>, a float with a value of 3.14</li>
<li><code>i_understand_annotations</code>, a boolean with a value of True</li>
<li><code>school</code>, a string with a value of “Holberton”</li>
</ul>

<pre><code>bob@dylan:~$ cat 4-main.py
#!/usr/bin/env python3

a = __import__('4-define_variables').a
pi = __import__('4-define_variables').pi
i_understand_annotations = __import__('4-define_variables').i_understand_annotations
school = __import__('4-define_variables').school

print("a is a {} with a value of {}".format(type(a), a))
print("pi is a {} with a value of {}".format(type(pi), pi))
print("i_understand_annotations is a {} with a value of {}".format(type(i_understand_annotations), i_understand_annotations))
print("school is a {} with a value of {}".format(type(school), school))

bob@dylan:~$ ./4-main.py
a is a &lt;class 'int'&gt; with a value of 1
pi is a &lt;class 'float'&gt; with a value of 3.14
i_understand_annotations is a &lt;class 'bool'&gt; with a value of True
school is a &lt;class 'str'&gt; with a value of Holberton
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x00-python_variable_annotations</code></li>
            <li>File: <code>4-define_variables.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11616">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11616" data-batch-id="62" data-toggle="modal" data-target="#task-11616-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11616-users-done-modal" data-task-id="11616" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "4. Define variables"</h4>
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


      <button class="btn btn-default btn-sm check-your-task-11616-modal-button" data-task-id="11616" data-toggle="modal" data-target="#task-test-correction-11616-correction-modal" id="task-num-4-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11616}">
          Check your code
      </button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-11616-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">Correction of "4. Define variables"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="11616">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>
                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="11616">
        <i aria-hidden="true" class="fa-solid fa-circle-info "></i>
    </button>
    <div class="help-container" data-task-id="11616">
        <div class="check-line">
            <div class="check-inline requirement success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div>
    </div>
</div>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11616}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11617" data-position="6" id="task-num-5">
      <div class="panel panel-default task-card " id="task-11617">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      5. Complex types - list of floats
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
    <p>Write a type-annotated function <code>sum_list</code> which takes a list <code>input_list</code> of floats as argument and returns their sum as a float.</p>

<pre><code>bob@dylan:~$ cat 5-main.py
#!/usr/bin/env python3

sum_list = __import__('5-sum_list').sum_list

floats = [3.14, 1.11, 2.22]
floats_sum = sum_list(floats)
print(floats_sum == sum(floats))
print(sum_list.__annotations__)
print("sum_list(floats) returns {} which is a {}".format(floats_sum, type(floats_sum)))

bob@dylan:~$ ./5-main.py
True
{'input_list': typing.List[float], 'return': &lt;class 'float'&gt;}
sum_list(floats) returns 6.470000000000001 which is a &lt;class 'float'&gt;
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x00-python_variable_annotations</code></li>
            <li>File: <code>5-sum_list.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11617">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11617" data-batch-id="62" data-toggle="modal" data-target="#task-11617-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11617-users-done-modal" data-task-id="11617" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "5. Complex types - list of floats"</h4>
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


      <button class="btn btn-default btn-sm check-your-task-11617-modal-button" data-task-id="11617" data-toggle="modal" data-target="#task-test-correction-11617-correction-modal" id="task-num-5-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11617}">
          Check your code
      </button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-11617-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">Correction of "5. Complex types - list of floats"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="11617">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>
                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="11617">
        <i aria-hidden="true" class="fa-solid fa-circle-info "></i>
    </button>
    <div class="help-container" data-task-id="11617">
        <div class="check-line">
            <div class="check-inline requirement success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div>
    </div>
</div>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11617}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11618" data-position="7" id="task-num-6">
      <div class="panel panel-default task-card " id="task-11618">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      6. Complex types - mixed list
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
    <p>Write a type-annotated function <code>sum_mixed_list</code> which takes a list <code>mxd_lst</code> of integers and floats and returns their sum as a float.</p>

<pre><code>bob@dylan:~$ cat 6-main.py
#!/usr/bin/env python3

sum_mixed_list = __import__('6-sum_mixed_list').sum_mixed_list

print(sum_mixed_list.__annotations__)
mixed = [5, 4, 3.14, 666, 0.99]
ans = sum_mixed_list(mixed)
print(ans == sum(mixed))
print("sum_mixed_list(mixed) returns {} which is a {}".format(ans, type(ans)))

bob@dylan:~$ ./6-main.py
{'mxd_lst': typing.List[typing.Union[int, float]], 'return': &lt;class 'float'&gt;}
True
sum_mixed_list(mixed) returns 679.13 which is a &lt;class 'float'&gt;
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x00-python_variable_annotations</code></li>
            <li>File: <code>6-sum_mixed_list.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11618">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11618" data-batch-id="62" data-toggle="modal" data-target="#task-11618-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11618-users-done-modal" data-task-id="11618" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "6. Complex types - mixed list"</h4>
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


      <button class="btn btn-default btn-sm check-your-task-11618-modal-button" data-task-id="11618" data-toggle="modal" data-target="#task-test-correction-11618-correction-modal" id="task-num-6-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11618}">
          Check your code
      </button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-11618-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">Correction of "6. Complex types - mixed list"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="11618">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>
                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="11618">
        <i aria-hidden="true" class="fa-solid fa-circle-info "></i>
    </button>
    <div class="help-container" data-task-id="11618">
        <div class="check-line">
            <div class="check-inline requirement success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div>
    </div>
</div>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11618}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11619" data-position="8" id="task-num-7">
      <div class="panel panel-default task-card " id="task-11619">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      7. Complex types - string and int/float to tuple
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
    <p>Write a type-annotated function <code>to_kv</code> that takes a string <code>k</code> and an int OR float <code>v</code> as arguments and returns a tuple. The first element of the tuple is the string <code>k</code>. The second element is the square of the int/float <code>v</code> and should be annotated as a float.</p>

<pre><code>bob@dylan:~$ cat 7-main.py
#!/usr/bin/env python3

to_kv = __import__('7-to_kv').to_kv

print(to_kv.__annotations__)
print(to_kv("eggs", 3))
print(to_kv("school", 0.02))

bob@dylan:~$ ./7-main.py
{'k': &lt;class 'str'&gt;, 'v': typing.Union[int, float], 'return': typing.Tuple[str, float]}
('eggs', 9)
('school', 0.0004)
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x00-python_variable_annotations</code></li>
            <li>File: <code>7-to_kv.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11619">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11619" data-batch-id="62" data-toggle="modal" data-target="#task-11619-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11619-users-done-modal" data-task-id="11619" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "7. Complex types - string and int/float to tuple"</h4>
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


      <button class="btn btn-default btn-sm check-your-task-11619-modal-button" data-task-id="11619" data-toggle="modal" data-target="#task-test-correction-11619-correction-modal" id="task-num-7-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11619}">
          Check your code
      </button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-11619-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">Correction of "7. Complex types - string and int/float to tuple"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="11619">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>
                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="11619">
        <i aria-hidden="true" class="fa-solid fa-circle-info "></i>
    </button>
    <div class="help-container" data-task-id="11619">
        <div class="check-line">
            <div class="check-inline requirement success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div>
    </div>
</div>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11619}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11620" data-position="9" id="task-num-8">
      <div class="panel panel-default task-card " id="task-11620">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      8. Complex types - functions
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
    <p>Write a type-annotated function <code>make_multiplier</code> that takes a float <code>multiplier</code> as argument and returns a function that multiplies a float by <code>multiplier</code>.</p>

<pre><code>bob@dylan:~$ cat 8-main.py
#!/usr/bin/env python3

make_multiplier = __import__('8-make_multiplier').make_multiplier
print(make_multiplier.__annotations__)
fun = make_multiplier(2.22)
print("{}".format(fun(2.22)))

bob@dylan:~$ ./8-main.py
{'multiplier': &lt;class 'float'&gt;, 'return': typing.Callable[[float], float]}
4.928400000000001
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x00-python_variable_annotations</code></li>
            <li>File: <code>8-make_multiplier.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11620">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11620" data-batch-id="62" data-toggle="modal" data-target="#task-11620-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11620-users-done-modal" data-task-id="11620" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "8. Complex types - functions"</h4>
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


      <button class="btn btn-default btn-sm check-your-task-11620-modal-button" data-task-id="11620" data-toggle="modal" data-target="#task-test-correction-11620-correction-modal" id="task-num-8-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11620}">
          Check your code
      </button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-11620-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">Correction of "8. Complex types - functions"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="11620">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>
                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="11620">
        <i aria-hidden="true" class="fa-solid fa-circle-info "></i>
    </button>
    <div class="help-container" data-task-id="11620">
        <div class="check-line">
            <div class="check-inline requirement success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div>
    </div>
</div>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11620}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11621" data-position="10" id="task-num-9">
      <div class="panel panel-default task-card " id="task-11621">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      9. Let's duck type an iterable object
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
    <p>Annotate the below function’s parameters and return values with the appropriate types</p>

<pre><code>def element_length(lst):
    return [(i, len(i)) for i in lst]
</code></pre>

<pre><code>bob@dylan:~$ cat 9-main.py 
#!/usr/bin/env python3

element_length =  __import__('9-element_length').element_length

print(element_length.__annotations__)

bob@dylan:~$ ./9-main.py 
{'lst': typing.Iterable[typing.Sequence], 'return': typing.List[typing.Tuple[typing.Sequence, int]]}
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-python</code></li>
            <li>Directory: <code>0x00-python_variable_annotations</code></li>
            <li>File: <code>9-element_length.py</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11621">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11621" data-batch-id="62" data-toggle="modal" data-target="#task-11621-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11621-users-done-modal" data-task-id="11621" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "9. Let's duck type an iterable object"</h4>
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


      <button class="btn btn-default btn-sm check-your-task-11621-modal-button" data-task-id="11621" data-toggle="modal" data-target="#task-test-correction-11621-correction-modal" id="task-num-9-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11621}">
          Check your code
      </button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-11621-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">Correction of "9. Let's duck type an iterable object"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="11621">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>
                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="11621">
        <i aria-hidden="true" class="fa-solid fa-circle-info "></i>
    </button>
    <div class="help-container" data-task-id="11621">
        <div class="check-line">
            <div class="check-inline requirement success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                <i aria-hidden="true" class="fa-solid fa-circle-check "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                <i aria-hidden="true" class="fa-solid fa-circle-xmark "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div>
    </div>
</div>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11621}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>

    <p class="lg-gap">
      </p><form class="button_to" method="post" action="/projects/1229/unlock_optionals"><input id="unlock_optional_btn" class="btn btn-primary btn-block" data-confirm="Are you sure? Make sure you focused on the mandatory tasks first" data-disable-with="Unlocking 3 advanced tasks..." data-gtm-custom-event-name="project_unlock_advanced_tasks" type="submit" value="Done with the mandatory tasks? Unlock 3 advanced tasks now!"><input type="hidden" name="authenticity_token" value="Eh6HjmUnTi-r_4KCL0N3ysBXzm3O3koLWp7D7e7HP-2BT7riMRRVPMh_tj8zyKyD0xNGd-6V5Ilxayyccb-t1Q" autocomplete="off"></form>
    <p></p>




          <div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;available&quot;:true,&quot;description&quot;:&quot;\u003cp\u003eUbuntu 18.04 with Python 3.7\u003c/p\u003e\n&quot;,&quot;id&quot;:23,&quot;name&quot;:&quot;Ubuntu 18.04 - Python 3.7&quot;,&quot;online&quot;:true}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;hkfoKjOmLbPQAOHC0cmW9y84ltnMitq_oGwUhWLJsGoVFtVGZ5U2oLOA1X_NQk2-PHwew-zBdD2Lmfv0_bEiUg&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"><div><div class="d-flex gap-4 sandboxes-filters"><a class="btn btn-outline-primary"><i aria-hidden="true" class="fa-solid fa-filter"></i><span class="ml-2">Running only</span></a><div class="align-items-center d-flex" style="position: relative; width: 100%;"><input class="form-control" placeholder="Search for an image ..." type="search" value=""></div></div><div class="mt-3"><h3>1 image<small class="ml-2">(0/2 Sandboxes spawned)</small></h3></div><div class="mt-3"><div class="panel panel-default"><div class="panel-body"><div class="align-items-center d-flex flex-wrap justify-content-between"><div><h3 class="mt-0"><i aria-hidden="true" class="fa-solid fa-terminal text-danger"></i><span class="ml-2">Ubuntu 18.04 - Python 3.7</span></h3><div class="mt-2 text-muted"><p>Ubuntu 18.04 with Python 3.7</p>
</div></div><div class="d-flex flex-wrap gap-5"><a class="btn btn-success"><i aria-hidden="true" class="fa-solid fa-play"></i><span class="ml-2">Run</span></a></div></div></div></div></div></div></div></div></div></div></div>

  </div>
</div>

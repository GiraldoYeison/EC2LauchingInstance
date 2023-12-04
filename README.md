# EC2LauchingInstance
How to create an AWS EC2 Instance / Launching EC2 Instance in AWS

<h1>Launching Amazon EC2 Instances | Steps to Configure and Manage Instances</h1>
<div><b>Creation Date:</b> October 18, 2023</div>
<div><b>Created By:</b> Yeison Giraldo</div>

<div style="height: 24px">&#8203;</div>
<hr />
<div style="height: 24px">&#8203;</div>


<div><h2><a href="https://labs.skillbuilder.aws/sa/lab/arn%3Aaws%3Alearningcontent%3Aus-east-1%3A470679935125%3Ablueprintversion%2FSPL-BE-200-CPBDEC-1%3A1.0.5-d7f74c93/en-US/ae717f00-ab64-4993-bde1-3d3c2cf24255::vM1FiRnnU4DQ6NQQ82o4ga"># Launching Amazon EC2 Instances | Self-Paced Labs</a></h2></div>

<div><h3>Log in to AWS</h3>

</div>

<div><h2><a href="https://us-west-2.console.aws.amazon.com/console/home?locale=en-US&region=us-west-2#"># Console Home | us-west-2</a></h2></div>

<div><h3>2. Type "EC2"</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/7088d34c-bc5a-40fb-9765-2a3fa071bc5e/8c2362e0-d531-44d2-bc5d-169ddeb32e03.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2686&fp-y=0.0254&fp-z=1.5759&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=192&mark-y=5&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzMmaD00NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;ec2&quot;" />
</div>

<div><h3>3. Click on EC2</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/4023b1c7-480b-49ac-8c43-e41fc9fb4e36/f2204ade-47cd-4e59-9a25-8c9219c8d15b.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3007&fp-y=0.2351&fp-z=3.0520&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=556&mark-y=303&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz04NyZoPTU2JmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on EC2" />
</div>

<div><h3>4. Click on Launch instance</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/2f7bc331-0762-44ad-8760-54a4e10710ae/cccb84cc-7858-4eb3-8039-2e23f73d0afd.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2259&fp-y=0.5653&fp-z=2.5618&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=461&mark-y=294&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNzgmaD03NSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Launch instance" />
</div>

<div><h3>5. Type "myFirstInstance"</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/8813ec03-4fc5-4261-88a5-95b8f301f961/610d9918-f1be-4a2e-a2dc-ac3a5443d33f.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2280&fp-y=0.3761&fp-z=1.5654&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=110&mark-y=308&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzYmaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;myFirstInstance&quot;" />
</div>

<div><h3>6. Click on Amazon Linux</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/b81ae7b0-9fec-4d30-a8ce-fede9172b9f3/c911187e-2faf-4c90-af5c-375843f4341b.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.0922&fp-y=0.3838&fp-z=2.2310&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=165&mark-y=222&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xNjMmaD0yMTkmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Amazon Linux" />
</div>

<div><h3>7. Click on Amazon Linux 2023 AMI…</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/d2f98af2-1bf5-4fc0-83ad-dcb05c408194/3ffbb30a-b038-47b1-bcf1-5526a55b3fda.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2860&fp-y=0.5398&fp-z=1.3248&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=93&mark-y=296&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03MjMmaD03MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Amazon Linux 2023 AMI…" />
</div>

<div><h3>8. Click on t2.micro…</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/ffe40931-5a18-4401-98fe-39c7b94b023a/1ec2b172-f8af-4a38-ac01-700edbadf3e0.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.5564&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=262&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD0xMzkmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on t2.micro…" />
</div>

<div><h3>9. Click on Select</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/03b4fe74-6c5f-4155-9bda-0330a590cdf2/4204f091-45b8-47f6-8aaf-cb973f6fc453.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.7876&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=417&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select" />
</div>

<div><h3>10. Click on Create new key pair or select a previous key</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/0f52de8c-e6fc-4a6d-8b85-9f1b5fcba332/52c98c83-bd4c-472c-8d9b-bf4bf5269e41.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4618&fp-y=0.7876&fp-z=2.6233&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=472&mark-y=302&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNTYmaD01OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create new key pair" />
</div>

<div><h3>11. Type "myFirstInsance"</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/89e8f00e-8507-43f8-9e65-d259d6df2cf6/77108dac-782e-410a-8a48-bc5e42b45fde.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5122&fp-y=0.3153&fp-z=1.5462&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=278&mark-y=300&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02NDMmaD00NSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;myFirstInsance&quot;" />
</div>

<div><h3>12. Click on Create key pair</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/85b7ae0f-76b8-40cc-a456-e95ed057bd37/b12deeed-7fe9-475e-aa90-d14a49e6f125.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.6392&fp-y=0.8230&fp-z=2.5459&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=458&mark-y=327&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yODMmaD03NSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create key pair" />
</div>

<div><h3>13. Click on Cancel If you already hae a Key</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/0249f673-db8d-4244-8b71-03703fd31f57/ee67c5ba-140d-497e-bcc4-e6fd6f2a1d3f.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5638&fp-y=0.8595&fp-z=2.7933&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=503&mark-y=361&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xOTQmaD04MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Cancel" />
</div>

<div><h3>14. Click on Select</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/82e57b5b-6b2c-4eb3-a2e6-bf63ba4ffc9a/3e548bd8-12d1-4706-aa47-2a55e0c4edac.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.7876&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=417&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select" />
</div>

<div><h3>15. Click on AWSLabsKeyPair-nLUQRGfr26AkvGhSYuojFN…</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/00691d48-62ff-4983-a225-e25ab36de695/7e386c07-bc86-4be9-967d-21c040166ff0.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2253&fp-y=0.7423&fp-z=1.5789&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=359&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MzImaD02NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on AWSLabsKeyPair-nLUQRGfr26AkvGhSYuojFN…" />
</div>

<div><h3>16. Click on Network settings Info…</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/a4160934-b820-4700-bd68-e511b87f0460/17ed369b-3937-42c6-93ff-0c8ef477aa1a.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2860&fp-y=0.5907&fp-z=1.3248&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=93&mark-y=51&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03MjMmaD01NjEmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Network settings Info…" />
</div>

<div><h3>17. Click on Number of instances  Info…</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/d5734f08-9910-43ef-9e60-39b7f64d7023/01511699-725e-4e7a-a4b3-a9ef6a28504b.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.6520&fp-y=0.4729&fp-z=1.1414&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=564&mark-y=67&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zMTkmaD01MjgmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Number of instances  Info…" />
</div>

<div><h3>18. Click on Launch instance</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/eee6b4d2-a8ad-4097-9d2d-acb47a357a8f/262a19fd-fdfe-43ad-937f-17fdda32c221.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7076&fp-y=0.8584&fp-z=2.9302&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=428&mark-y=345&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNDMmaD04NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Launch instance" />
</div>

<div><h3>19. Click on i-00b9ef68ab525e595</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/25bf48fb-1bc6-44be-a4d1-0934140588fd/db3fd43e-871d-4111-948a-6329b5308fdd.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2732&fp-y=0.1781&fp-z=2.5498&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=459&mark-y=276&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yODImaD00OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on i-00b9ef68ab525e595" />
</div>

<div><h3>20. Click on Instances</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/89e37f50-ad8b-4b17-bfaa-90d1fba72f4b/815318ed-9b6a-41e0-a8cb-b511f754eef1.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.9750&fp-y=0.2212&fp-z=1.1683&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=0&mark-y=140&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yMzMwJmg9NjImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Instances" />
</div>



<div><h2><a href="https://us-west-2.console.aws.amazon.com/ec2/home?region=us-west-2#Instances:instanceId=i-00b9ef68ab525e595"># Instances | EC2 | us-west-2</a></h2></div>

<div><h3>22. Click on Instance state</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/dcba794e-dec6-4ecd-832f-550fa1a191c9/62ee6755-9cb8-4fc7-a4b8-5d0c7223be9d.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7531&fp-y=0.0719&fp-z=2.9427&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=422&mark-y=101&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNTYmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Instance state" />
</div>


<div><h3>24. Click on Stop instance</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/299ed767-76f1-4b93-aedc-71c4295d4465/4eda0d58-42cd-4f26-80cb-ecf8b868cd70.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7598&fp-y=0.1051&fp-z=2.9237&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=402&mark-y=163&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zOTYmaD04MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Stop instance" />
</div>

<div><h3>25. Click on Stop</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/d08baa84-06fe-41d2-a74b-538be9e94a4f/958ccc01-3597-4c2e-9542-2d0015812f16.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7216&fp-y=0.6040&fp-z=2.9427&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=512&mark-y=292&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xNzcmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Stop" />
</div>

<div><h2><a href="https://labs.skillbuilder.aws/sa/lab/arn%3Aaws%3Alearningcontent%3Aus-east-1%3A470679935125%3Ablueprintversion%2FSPL-BE-200-CPBDEC-1%3A1.0.5-d7f74c93/en-US/ae717f00-ab64-4993-bde1-3d3c2cf24255::vM1FiRnnU4DQ6NQQ82o4ga"># Launching Amazon EC2 Instances | Self-Paced Labs</a></h2></div>

<div><h3>26. Click on Instance Stop/Start: When you stop your instance, it enters the Stopping state, and then the Stopped state. When you stop and start your instance, you lose any data on the instance store volumes on the previous host computer. However, the instance retains its private IPv…</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/ccc745c5-80c9-4b96-b324-b312fd65c0e0/2a031087-56fd-4cab-ae48-2163d447c009.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5979&fp-y=0.6230&fp-z=1.3298&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=42&mark-y=135&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xMTE3Jmg9NDk4JmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Instance Stop/Start: When you stop your instance, it enters the Stopping state, and then the Stopped state. When you stop and start your instance, you lose any data on the instance store volumes on the previous host computer. However, the instance retains its private IPv…" />
</div>

<div><h2><a href="https://us-west-2.console.aws.amazon.com/ec2/home?region=us-west-2#Instances:instanceId=i-00b9ef68ab525e595"># Instances | EC2 | us-west-2</a></h2></div>

<div><h3>27. Click on Actions</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/9e3a5a1b-1cf2-4460-992c-f14c5ed13950/7cc73a2f-b377-4c96-ae6c-5751d7859b2c.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8294&fp-y=0.1117&fp-z=2.9427&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=470&mark-y=179&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNjEmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Actions" />
</div>

<div><h3>28. Click on View details</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/30eb2c11-eb4e-4c5f-bbee-7cb68b19fcaf/13e11abc-891a-45a5-86c4-4e5f2e2c2a4a.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8697&fp-y=0.1792&fp-z=2.9237&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=474&mark-y=290&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz01MzgmaD04MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on View details" />
</div>

<div><h3>29. Click on Instance summary for i-00b9ef68ab525e595 (myFirstInstance)…</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/2dc5ba02-0444-4b5d-9658-f6f4e9c04c8c/dc7a96e2-2e51-443e-a3bc-1f44663628fa.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5681&fp-y=0.1787&fp-z=1.1887&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=16&mark-y=107&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xMTY4Jmg9NjcmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Instance summary for i-00b9ef68ab525e595 (myFirstInstance)…" />
</div>

<div><h3>30. Click on Instance state</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/6f7f3d01-d45d-46c1-bf00-710e1c7fad75/48a9d766-78e7-4d33-af86-84480f442fc2.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8416&fp-y=0.1670&fp-z=2.9427&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=463&mark-y=287&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNTYmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Instance state" />
</div>

<div><h3>31. Click on Terminate instance</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/5402afdc-0006-471e-8d51-b342a882b296/c5cf7e77-f1ac-46c3-b001-55ad93edfec1.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8483&fp-y=0.3374&fp-z=2.9237&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=470&mark-y=290&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zOTYmaD04MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Terminate instance" />
</div>

<div><h3>32. Click on Terminate</h3>
<img src="https://images.tango.us/workflows/6c571592-f2b7-400e-9e76-c8a83d8da488/steps/b0443d60-dd88-4c38-9b47-1026d3cbee75/f16f67ef-bdd0-43b2-bb8c-2211233cd87f.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7775&fp-y=0.6737&fp-z=2.9427&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=472&mark-y=292&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNTcmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Terminate" />
</div>

<br/>
<hr/>
<div><h3>You have configure your First AWS EC2 Instance, CONGRATULATIONS! </h3>
</div>

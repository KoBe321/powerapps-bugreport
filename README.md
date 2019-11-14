Create the app.

Modify it:

![](./pics/start_code.PNG)

Run `msbuild /t:restore` and `msbuild`.

Import:

![](./pics/choose_file_1.PNG)

![](./pics/import_1.PNG)

![](./pics/imported_1.PNG)

Code working in an empty Canvas app:

![](./pics/result_1.PNG)

Modify component:

![](./pics/start_code_2.PNG)

Modify XML:

![](./pics/xml.PNG)

It's ok in development mode:

![](./pics/dev_mode.PNG)

Run `msbuild /t:restore` and `msbuild`.

Re-import the solution.
The pop-up windows are the same, I won't attach the pictures again. :)

Re-open the app:

![](./pics/danger.PNG)

Only a welcome message is shown:

![](./pics/welcome.PNG)

The name of the previously import component has changed:

![](./pics/prev_app_name.PNG)

After re-importing the component, 2 components are shown:

![](./pics/2_comps.PNG)

The component is still the old one:

![](./pics/not_updated.PNG)

I've deleted all my former solutions, but their components are still visible - why?

![](./pics/deleted.PNG)

# Graphics Task 6 Skeleton

For each of the 6 tasks, upload the provided skeleton files to https://shaderlabweb.doc.ic.ac.uk/ and edit them using
the online editor.

The main difference between the provided skeleton jsons and the default ShaderLab json is the ``lightPosition`` and ``lightInCamspace`` uniforms, which you should use in your answers.
For this exercise we recommend you keep lightInCamspace=False, lightPosition=(6, 4, 3).

To test, commit them in this repository and run the LabTS script.
LabTS allows you to see what the marker will, detailing the setup parameters and viewing your solution from different
angles.

Files to submit:
 - task_6a.json
 - task_6b.json
 - task_6_extension_screenshot.png

## FAQ

### Why does it look different on LabTS

LabTS resets lots of camera/model parameters, all detailed at the beginning of the report.
If you've copied those and it still looks different, try loading it in Firefox (LabTS uses a virtual Firefox browser).
LabTS also uses a virtual display with resolution 1024x768, but this should only make very minor differences.

### Why is it black on LabTS?

Try looking at the ShaderLabWeb log at the bottom of the report.

Possible sneaky errors
 + Differences in precision of browsers, look for ``precision (high|medium)p float`` towards the top of the shader.

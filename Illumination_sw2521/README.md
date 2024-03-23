# Graphics Task 3 Skeleton

For each of the 3 tasks, upload the provided skeleton files to https://shaderlabweb.doc.ic.ac.uk/ and edit them using
the online editor.

The main difference between the provided skeleton jsons and the default ShaderLab json is the ``lightPosition`` and ``lightInCamspace`` uniforms, which you should use in your answers.

To test, commit them in this repository and run the LabTS script.
LabTS allows you to see what the marker will, detailing the setup parameters and viewing your solution from different
angles.

Files to submit:
 - task_3a.json
 - task_3b.json
 - task_3c.json

## FAQ

### Why does it look different on LabTS

LabTS resets lots of camera/model parameters, all detailed at the beginning of the report.
If you've copied those and it still looks different, try loading it in Firefox (LabTS uses a virtual Firefox browser).

### Why is it black on LabTS?

Try looking at the ShaderLabWeb log at the bottom of the report.

Possible sneaky errors
 + Differences in precision of browsers, look for ``precision (high|medium)p float`` towards the top of the shader.
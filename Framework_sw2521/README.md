# Graphics Task 1 Skeleton

This is just a taster task to show you how the automated feedback system works.
Please do try submitting things through labts and report any potential bugs to the Graphics course team.

BUT this isn't assessed.

For each of the 1 tasks, upload the provided skeleton files to https://shaderlabweb.doc.ic.ac.uk/ and edit them using
the online editor.

The main difference between the provided skeleton jsons and the default ShaderLab json is the ``lightPosition`` and ``lightInCamspace`` uniforms, which you should use in your answers (for the later courseworks, don't worry about them for now).

To test, commit them in this repository and run the LabTS script.
LabTS allows you to see what the marker will, detailing the setup parameters and viewing your solution from different
angles.

Files to submit:
 - task_1a.json

## FAQ

### Why does it look different on LabTS

LabTS resets lots of camera/model parameters, all detailed at the beginning of the report.
If you've copied those and it still looks different, try loading it in Firefox (LabTS uses a virtual Firefox browser).

### Why is it black on LabTS?

Try looking at the ShaderLabWeb log at the bottom of the report.

Possible sneaky errors
 + Differences in precision of browsers, look for ``precision (high|medium)p float`` towards the top of the shader.

# AI Photo Editing with Inpainting using Segment-Anything-Model (SAM)


### Project Summary

This project builds the backend for an AI photo editing app that allows users to select a subject in an image and change its background, or keep the background and change the subject. The app uses the Segment Anything Model (SAM) to create a mask around the selected object, and then uses a text2image diffusion model to generate a new background or subject. The user can also choose to invert the mask and substitute the subject while keeping the background. The project involves calling the SAM model and processing its output, as well as using a text2image diffusion model to generate the new background or subject.

### Project Example

The following image shows an example of the app in action with just 'basketball' used the proompt for the infill. 

![Input Exxample](/images/Screenshot%202024-10-13%20210332.png)

![Output Example](/images/image.png) 


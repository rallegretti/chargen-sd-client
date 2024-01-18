# Stable Diffusion Character Portrait Generator
A client page in HTML, Javascript, and JQuery to generate character portraits from a Stable Diffusion API

This is based on an Automatic1111 deployment running on the same machine that this page is loaded from.
The script is well-documented and changes should be easy to make to suit your deployment needs

Automatic1111 must be run with the command line arguments:

--api   (this enables image generation from API calls)

--cors-allow-origins "*"    (this allows machines on other ports/addresses to access the API without errors)

More information on Automatic1111 and setup can be found at https://github.com/AUTOMATIC1111/stable-diffusion-webui

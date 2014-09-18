ansible-ffmpeg-build
====================

### 2014-09-18:

I've updated this playbook to work with [Ansible 1.7.1](http://www.ansible.com/blog/page/9). Recently, I've started using Docker for the system this was being applied to. Find the Dockerfile and resulting image below.

[Dockerfile](https://github.com/ozzyjohnson/docker-ffmpeg-webm)

[Automated Build](https://registry.hub.docker.com/u/ozzyjohnson/ffmpeg-webm/)


### Description:

A simple playbook to clone and build ffmpeg + some useful codecs from source. 

I put this together for building/updating the master template for a set of virtual machines which generate VP8 files from RTP streams generated by Cisco IP cameras for easy viewing in a web browser.

Based on the [Ubuntu Compilation Guide](https://trac.ffmpeg.org/wiki/CompilationGuide/Ubuntu).


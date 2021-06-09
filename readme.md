## Introduction

Valet *WSL* is a Laravel development environment for WSL minimalists. No Vagrant, no `/etc/hosts` file. You can even share your sites publicly using local tunnels. _Yeah, we like it too._

Valet *WSL* configures your system to always run Nginx in the background when your machine starts. Then, using [Acrylic DNS Proxy](https://mayakron.altervista.org/support/acrylic/Home.htm), Valet proxies all requests on the `*.test` domain to point to sites installed on your local machine.

In other words, a blazing fast Laravel development environment that uses roughly 7mb of RAM. Valet *WSL* isn't a complete replacement for Vagrant or Homestead, but provides a great alternative if you want flexible basics, prefer extreme speed, or are working on a machine with a limited amount of RAM.

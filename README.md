This is an environment cookbook.

The only intended usage is for someone to systimatically control exactly what
the 'devhelper-production' environment is set to. Most specifically, what are
the exact values of the cookbooks?

To use this cookbook, modify the Berksfile as desired, run `berks install`, then `berks apply devhelper-production`

FROM almalinux:9 
#CMD ["ping", "google.com"] 
# CMD instrction can be overridden during run time 
#ENTRYPOINT ["ping", "facebook.com"]
# We can't overridden the ENTRYPOINT instructions, but when we are trying to do override it will happen append to the existing command
# For better improovement we can use both instruction together by providing command in ENTRYPOINT and options/default options in CMD instruction means user can override the default options through cmd line at run time
CMD ["google.com"]
ENTRYPOINT ["ping"]
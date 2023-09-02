Genesys Cloud Platform SDK Command Line Interface 

CLI Command usage: 

 gc conversations get b6d58e25-0a81-4d33-9166-a30288c89c56 --profile \<profile> --transform CustomerPartData.gotmpl

here, --Profile refers to section [<profile>]  in the file C:\Users\\<user>\.gc\config.toml   where client id, secret, access token etc. are stored. 
GC executable must be installed in the PATH

Alternatively, you can call the 
 gc conversations get b6d58e25-0a81-4d33-9166-a30288c89c56 --profile hm_fbt --transform https://github.com/besthand70/gcpsdkcli/Participant%20Data/CustomerPartData.gotmpl 

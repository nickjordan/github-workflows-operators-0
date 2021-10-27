## Usage 
### Release Operator Workflow 
Required Github Secrets:
```

      REGISTRY_USERNAME:
        description: 'Username for Registry'
        required: true
      REGISTRY_PASSWORD:
        description: 'Password for Registry'
        required: true

## Optional Github Secrets 

```
### Workflow Inputs: 
(Optional) 
      BUILD_PLATFORMS: 
        description: 'Comma separated list of targets for buildse.g. linux/amd64,linux/arm64,linux/ppc64le'
        required: false

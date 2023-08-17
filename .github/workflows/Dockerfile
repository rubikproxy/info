- name: Build and push container image to registry
  uses: docker/build-push-action@v3
  with:
    push: true
    tags: index.docker.io/${{ secrets.AzureAppService_ContainerUsername_08ecb3f97fd140f69ff55e2efd6cf949 }}/mcr.microsoft.com/appsvc/staticsite:${{ github.sha }}
    file: ./.github/workflows/Dockerfile

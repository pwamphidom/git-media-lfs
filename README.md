# Demo Repo With Git LFS Support

- Files in this repository are all pushed from the local machine through `git push`.
- The `.gitattributes` is created before adding any target files
- Hence, the large files (videos and images under the `large-image` folder) are correctly indexed. You can verify by calling `git lfs ls-files` in the terminal

**NOTE:** For large files uploaded before LFS config, you'll need to remove them from your repository. You can take references from the documentation: https://docs.github.com/en/repositories/working-with-files/managing-large-files/moving-a-file-in-your-repository-to-git-large-file-storage


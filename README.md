# MobSF CI
This repo contains all the is required to run [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) in the Gitlab CI as a Service. This project is an alternative to Soluto's [mobsf-ci project] (https://github.com/Soluto/mobsf-ci). You can read more about the project [here](https://waristea.medium.com/running-mobsf-sast-using-gitlab-ci-service-7c3ac3a48648).

## Usage
1. Clone the repo
2. Modify the variables in `.gitlab-ci.yml.template` 
3. Rename the `.gitlab-ci.yml.template` to `.gitlab-ci.yml` and copy it to the project that contains the APK. Or integrate it to your already-established `.gitlab-ci.yml`.
4. (Optional) If you want to modify the `scan.rb`, remember to modify the `git clone https://github.com/waristea/mobsf-ci.git` to point to your Git repo containing the modified `scan.rb` and its dependencies. To change the content of `scan.rb` you can refer to MobSF API docs in your local MobSF instance (https://127.0.0.1:8000/api_docs)

## Contributing
Please feel free to contribute to this project :)

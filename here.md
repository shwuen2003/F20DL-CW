## After cloning the repo...
1. Open Anaconda Prompt
2. Create a new environment in Anaconda <br>
Run `conda create --name F20DL_CW python=3.x`, and activate it by running `conda activate F20DL_CW` <br>
3. If someone install a new package, you need to update the `environment.yml` by running `conda env export --no-builds > environment.yml`
4. After you pull the updated `environment.yml`, you need to update your local environment as well by running `conda env update --file environment.yml --prune`

## How to push?
1. `git add .`
2. `git commit -m "Write your commit msg here"`
3. `git push -u origin main`

## How to pull?
1. `git pull origin main`

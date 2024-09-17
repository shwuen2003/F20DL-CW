## After cloning the repo...
1. Open Anaconda Prompt
2. Create a new environment in Anaconda <br>
Run `conda create --name F20DL_CW python=3.12.4`, and activate it by running `conda activate F20DL_CW`, set up the environment with the packages in `environment.yml` or `environment2.yml` by running: <br>
`conda env update --file environment.yml --prune` (For Window user) <br>
`conda env update --file environment2.yml --prune` (For Mac user) <br>
3. If wanna install a new package in environemnt, you need to update the `environment.yml` and `environment2.yml` as well by running `conda env export --no-builds > environment.yml` and `conda env export --no-builds > environment2.yml` <br>
** Please inform everyone if you have installed a new package!
5. After you pull the updated `environment.yml` or `environment2.yml`, you need to update your local environment as well by running `conda env update --file environment.yml --prune` or `conda env update --file environment2.yml --prune`

## How to push?
1. `git add .`
2. `git commit -m "Write your commit msg here"`
3. `git push -u origin main`

## How to pull?
1. `git pull origin main`

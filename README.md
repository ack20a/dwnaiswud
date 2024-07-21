#### GitHub Actions

1. 点击项目右上角进行**fork**

2. 然后点击你fork的项目中的**Settings**，找到**Secrets and variables**，选中**Actions**里的**New repository secret**添加一个环境变量，名称必须为**INVITE_CODE**

3. 点击你项目上方的**Actions**，第一次打开可能需要点击 `I understand...`，来启用actions

4. 提交修改来触发Actions，建议直接修改`run.py`，在空白的地方输入一次换行**commit**提交即可

5. 点开**Actions**查看运行日志
至此操作完成，每天早十点、晚六点十分各定时执行一次（可以自己到`/.github/workflows/run.yml`中修改定时），可以以同样方式进入**Actions**查看日志

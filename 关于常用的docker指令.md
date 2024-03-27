## 关于常用的docker指令

每次启动docker前，先需要打开docker的软件。

~~~linux
docker build -t plato -f Dockerfile .
./dockerrun.sh
./dockerrun_gpu.sh
# On Ubuntu Linux, you may need to add sudo before these docker commands.
docker ps -a
docker ps -s
docker start 8520d6f6f1eda9f16762a613bf214e46abaf24a832eeadc1da4314116ca453f5
docker attach 8520d6f6f1eda9f16762a613bf214e46abaf24a832eeadc1da4314116ca453f5
exit
docker stop 8520d6f6f1eda9f16762a613bf214e46abaf24a832eeadc1da4314116ca453f5
python ./examples/split_learning/llm_split_learning/split_learning_main.py -c ./examples/split_learning/llm_split_learning/split_learning_wikitext2_gpt2_lora.yml
~~~


# StudyVue
learning vue

# HBuilderx内置浏览器不能显示控制台
lsof -i:9777 | awk '{print $2}' | tail -n +2 | xargs kill -9

FROM node

# node.js の環境変数を定義する
# 本番環境では production
ENV NODE_ENV=development

# 起動後に実行するコマンドを指定(起動確認用）
# CMD if [ "${NODE_ENV}" = "development" ]; then \
#         npm run dev


CMD if [ ${NODE_ENV} = "development" ]; then \
        echo "NODE_ENV : development"; \
        npm run dev \
　　else \
        echo "NODE_ENV : production"; \
    fi;
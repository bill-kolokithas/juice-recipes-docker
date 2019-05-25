FROM nginx:1.15.10
COPY --from=juice_recipes_rails:latest /root/juice-recipes/public /web-assets
COPY nginx.conf /etc/nginx/

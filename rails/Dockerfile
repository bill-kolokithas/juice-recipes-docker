from rails:juice-recipes
WORKDIR /root/juice-recipes
ENV RAILS_ENV="production"
ENV RACK_ENV="production"
RUN bundle exec rake assets:precompile 2>/dev/null
EXPOSE 3000
ENTRYPOINT ["bundle", "exec"]
CMD ["puma", "-p", "3000"]

#First build docker file in ft-rails
#build it "docker build -t ex02 ."
#run "docker run -p 3000:3000 ex02"

FROM ft-rails:on-build
EXPOSE 3000
CMD ["rails", "s", "-b", "0.0.0.0", "-p", "3000"]
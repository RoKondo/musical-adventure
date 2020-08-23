FROM cartahub/devops

RUN echo "<h2> Rodrigo Yoshio Kondo rodi.kondo@gmail.com</h2>" >> app/templates/index.html
RUN echo $CIRCLE_BUILD_URL >> app/templates/index.html
CMD ["carta-devops", "serve"]



ARG version
FROM almalinux:$(version:-9)
#FROM almalinux:9
ENV course="devops" \
    duration="120mins"
ARG trainer="sivalumar"
ENV tranier=$(trainer)
RUN echo "Hi course is: $(course), duration is: $(duration), trainer is: $(trainer), version is: $(version)"
CMD ["sleep", "1000"]

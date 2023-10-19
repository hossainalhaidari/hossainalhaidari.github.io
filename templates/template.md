# {{it.title}}

{{@each(it.summary) => it}}
**{{it.title}}** {{it.value}}  
{{/each}}


# SKILLS
{{@each(it.skills) => it}}
**{{it.title}}**  
{{it.value}}


{{/each}}
# EDUCATIONS
{{@each(it.educations) => it}}
**{{it.name}}**, {{it.location}}  
*{{it.degree}}*  
*{{it.period}}*  
Grade Percentage: **{{it.gpa}}%**

{{/each}}
# EXPERIENCES
{{@each(it.experiences) => it}}
**{{it.company}}** — *{{it.period}}*  
{{it.website}}  
{{it.title}}  

{{/each}}
# PROJECTS
{{@each(it.projects) => it}}
**{{it.title}}**, {{it.company}} - *{{it.techStack}}*  
{{it.url}}  
*{{it.description}}*  

{{/each}}
# CERTIFICATES
{{@each(it.certificates) => it}}
- {{it.description}}
{{/each}}

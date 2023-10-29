### Summary of Systems Development Concepts

#### What is Systems Development?

Systems development is the structured process by which business requirements are converted into an operational IT system. The development process often involves multiple stages, including:

- A feasibility study to evaluate if the project is worth pursuing.
- Requirements engineering to analyze business needs and specify user requirements.
- System design to cater to user needs.
- Software development to meet those needs.
- Testing of the developed software.
- Implementation of the solution.


#### Relation to other branches of IT

 <img src="assets/images/summary.png" alt="Image showing the relations to other branches in IT">

- **Project Management**: Ensures proper planning and resource allocation for the development process.
- **Business Analysis**: Focuses on understanding business issues and opportunities that the IT system aims to address.
- **Systems Architecture**: Concerned with building a foundational blueprint for systems.
- **Testing**: A specialized discipline that aims to identify defects and assure system quality.
- **Configuration Management and Change Control**: Deals with managing system components and their relationships, and controlling changes in a structured manner.
- **Quality Control and Assurance**: Ensures that the system meets defined quality criteria.

#### Offshoring and Outsourcing

Numerous organizations opt to offshore or outsource their systems development, often with the aim of leveraging cost-effective, top-tier resources available in other nations, like India. Outsourcing entails entrusting development tasks to specialized IT companies, which may also involve offshoring. These approaches bring forth their distinct advantages and obstacles, including issues like communication barriers and the relinquishment of control over essential systems.

By gaining insight into these dimensions of systems development, organizations can more effectively navigate the intricacies and difficulties associated with constructing IT systems.

<ul>
{% for summary in site.summary %}
  <li>
    <a href="{{ summary.url }}">{{ summary.title }}</a>
  </li>
{% endfor %}
</ul>

<ul>
{% for summary in site.data.summary %}
  <li>
    {{ summary.title }} por {{ summary.author }}
  </li>
{% endfor %}
</ul>

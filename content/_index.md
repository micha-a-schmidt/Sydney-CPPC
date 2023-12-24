---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: '' 
      subtitle: ''
      text: Sydney Consortium for Particle Physics and Cosmology (Sydney-CPPC)
    design:
      columns: '1'
      background:
        image: 
          filename: bubbles-small.jpg
          filters:
            brightness: 0.7
          parallax: false
          position: center
          size: cover
        text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
 
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <img src="img/serpent.png" alt="Glashow's serpent" width="200" align="left" style="margin:0px 50px"/>
        Cosmology and particle physics describe nature at its largest and shortest distances, respectively. Both are intimately linked in the early universe with its extreme conditions of high temperature, densities and energies. This is depicted in the cosmic ouroboros. Our <a href="research">research</a> is focused on different aspects of this connection.

  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Academic Staff
          - Research Associates
          - Students
          - Honorary Staff
          - Former Members
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        Sydney-CPPC organizes a regular seminar series via [Zoom](https://uni-sydney.zoom.us/j/610935631) which is open to everyone. The usual times for the seminars are Thursdays at 16:00 Sydney time. Just click the link above to connect. The recordings of most of the seminars are available via our [Youtube channel](https://www.youtube.com/channel/UCtVYU6uw6Xu1UWq6OvLbpvg).

        Future and past seminars are listed on our [seminar indico page](https://indico.cern.ch/category/14675/), which also provides a [calendar](https://indico.cern.ch/export/categ/14675.ics?from=-31d) with all upcoming events.
        Similarly, future and past events are listed on [the events page](https://indico.cern.ch/category/12731/). 



  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'


  - block: markdown
    content:
      title:
      subtitle: ''
      text: |


        The Sydney Consortium for Particle Physics and Cosmology (Sydney-CPPC) consists
        of the <a href="https://www.physics.unsw.edu.au/our-research/research-areas/fundamental-physics">cosmology and particle physics group at the University of New South
        Wales Sydney</a>  and the <a href="http://www.physics.usyd.edu.au/hienergy/index.php/Main_Page">particle physics group at the University of
        Sydney</a>.

        <img src="img/usyd-bw.png" alt="University of Sydney" style="float:right; width: 33%; max-width: 500px; min-width: 200px"/>
        <img src="img/unsw.png" alt="UNSW" style="float: right; width: 30%; max-width: 500px; min-width: 200px"/>

---

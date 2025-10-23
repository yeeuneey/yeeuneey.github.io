---
title: "Contact"
summary: "Get in touch with Ye-eun Kim and find the campus location."
type: landing
layout: list
image:
  filename: "media/contact-banner.jpg"
  focal_point: "center"
  perview_only: false

sections:
  - block: markdown
    id: contact-banner
    content:
      text: |
        <figure class="page-banner">
          <img src="/media/contact-banner.jpg" alt="Contact page banner" loading="lazy">
        </figure>
    design:
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    id: contact-info
    content:
      title: "📞 Contact"
      text: |
        {{< icon name="envelope" pack="fas" >}} [202312632@jbnu.ac.kr](mailto:202312632@jbnu.ac.kr)
        
        {{< icon name="phone" pack="fas" >}} [+82-10-3370-7588](tel:+821033707588)

        {{< icon name="brands/github" pack="fab" >}} [yeeuneey](https://github.com/yeeuneey)

        {{< icon name="brands/discord" pack="fab" >}} [yeeuneey](https://discord.com/users/yeeuneey) 

        {{< icon name="brands/instagram" pack="fab" >}} [imyezlv](https://instagram.com/imyezlv)
    design:
      spacing:
        padding: [30, 0, 10, 0]

  - block: markdown
    id: map
    content:
      title: "📍 Location"
      text: |
        <p style="text-align:center; margin: 0 0 12px;">
          College of Engineering Building 7, 567 Baekje-daero, Deokjin-gu, Jeonju-si
        </p>

        <style>
          /* Desktop */
          .map-frame {
            width: 600px;
            height: 450px;
            border: 0;
            display: inline-block;
          }

          /* Mobile */
          @media (max-width: 768px) {
            .map-frame {
              width: 100%;
              height: 400px;
              display: block;
            }
          }
        </style>

        <div style="text-align:center; overflow:hidden;">
          <iframe
            class="map-frame"
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3903.0540515781927!2d127.13295709890805!3d35.84552462693218!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x35702330dc920b9d%3A0x1d0d425396006646!2z7KCE67aB64yA7ZWZ6rWQIOqzteqzvOuMgOs2VmSA37Zi46rSA!5e0!3m2!1sko!2skr!4v1760322660618!5m2!1sko!2skr"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade">
          </iframe>
        </div>
    design:
      spacing:
        padding: [8, 0, 60, 0]
---

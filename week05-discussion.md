# Week 5 Discussion: Using Hypothesis Testing to Make Smarter Project Decisions

> *This discussion shows how hypothesis testing helps validate project outcomes with data, improving decision-making and proving real business impact.*

---

## **Discussion Topic**
#### Describe the steps in hypothesis testing and discuss the differences between testing a population mean and a population proportion. Use an example for each and explain how results are interpreted. Cite your sources.

---

In project management, hypothesis testing could provide a structured approach for validating project outcomes and promoting *data-driven decisions.* The process involves five steps: stating your null and alternative hypotheses, selecting a significance level (typically *0.05*), choosing the appropriate test statistic, calculating the P-value, and making a decision based on the results (Triola, 2020).

When selecting what method to use, I need to factor in the type of data I have available to me. If I was measuring success rates, compliance percentages, or other yes/no outcomes, I would use **proportion tests** with z-statistics. When measuring performance metrics, think response times or processing speeds, I'd use **mean tests** with t-statistics.

For a lot of project managers, project success is often measured by completion rates. Hypothesis testing would allow me to *shift the focus* to actual performance improvements with statistical evidence.

**Proportion Example:**  
Testing if cybersecurity training increases compliance above a 60% baseline.  
H₀: p ≤ 0.60 vs H₁: p > 0.60. After training 200 employees, 138 comply (69%). Using z-test, P-value = 0.015. Since 0.015 < 0.05, **I reject H₀**: the data shows that the training initiatives have significantly improved company compliance.

**Mean Example:**  
Testing if server upgrades reduce response times from 4.2 seconds.  
H₀: μ = 4.2 vs H₁: μ < 4.2. Measuring 35 post-upgrade responses with mean = 3.7 seconds. Using t-test, P-value = 0.008. Since 0.008 < 0.05, **I reject H₀**: the data shows that the server upgrades have significantly reduced the standard response times.

This statistical approach would help me move beyond basic project metrics and demonstrate to key leadership how their IT investments are delivering *real*, measurable business results.

---

> **Reply from Classmate:**  
> Hi Gabrielle, you did a great job of determining whether hypothesis testing could support better decision-making in project management.
> 
> I like how you used clear examples for both proportion and mean, like checking if training increases compliance or if upgrades reduce response times. It really shows how statistics can help you prove whether the changes made a difference. I also love how you think beyond just statistics and how the data can show real value and importance. I am wondering, when looking at all these projects, how do you determine which performance metrics are worth testing?

> **Response from Gabrielle Dominguez:**  
> Thank you for your kind words and great question. Determining which performance metrics are *worth testing* is indeed a crucial consideration.  
>  
> When managing projects, I go back to the *'why'* behind the project we are working to complete. **What is the goal?** For example, if I am working on migrating an internal database to a new platform, the metric may be how many people are adopting the new system and using it in real time, instead of hesitating because they do not like change. In this case, I would test the *adoption rate* of the platform. I already know the migration was successful, but this gives me a new lens to look through: **how easy is it to use for an early adopter?**
> 
> Some projects are more nuanced than this, these are when they are opinion-based and there is no clear metric to measure. An example of this would be client satisfaction with a product or service. There is no inherent metric to measure satisfaction because *satisfaction* is their measurement. This is why many companies send surveys to try and put words or metrics to feelings.  
>  
> For example, you go to a restaurant and they send you a survey asking about your food, server, and experience. They could gather this data by using a 1–5 star rating system, **putting data to what was once only a feeling.**
>  
> Great question again, and I am looking forward to continuing to learn alongside you for the remainder of the semester.

---

## Hypothesis Test Visualizations

<!-- First Row -->
<div style="display: flex; flex-wrap: nowrap; max-width: 1100px; margin: 0 auto;">
  <div class="imageBorder">
    <img
      src="https://github.com/GabrielleDominguez/Statics-Applied-Bridging-Data-Decision-Making-in-Project-Management/blob/8ae61b643462fd795d5f333720f8b35436170685/Article%205%2C%20image%201%20v3.png?raw=true"
      alt="Hypothesis Image 1 v3"
      style="width: 100%; height: auto; display: block; cursor: pointer; border-radius: 0; transition: filter 0.3s ease;"
      class="zoomable"
    />
    <div class="plus">+</div>
  </div>

  <div class="imageBorder borderLeft">
    <img
      src="https://github.com/GabrielleDominguez/Statics-Applied-Bridging-Data-Decision-Making-in-Project-Management/blob/8ae61b643462fd795d5f333720f8b35436170685/Atricle%205%2C%20image%202%20v3.png?raw=true"
      alt="Hypothesis Image 2 v3"
      style="width: 100%; height: auto; display: block; cursor: pointer; border-radius: 0; transition: filter 0.3s ease;"
      class="zoomable"
    />
    <div class="plus">+</div>
  </div>
</div>

<!-- Second Row with spacing added -->
<div style="display: flex; flex-wrap: nowrap; max-width: 1100px; margin: 12px auto 0 auto;">
  <div class="imageBorder">
    <img
      src="https://github.com/GabrielleDominguez/Statics-Applied-Bridging-Data-Decision-Making-in-Project-Management/blob/65156eaf56ca57c55cff72637c17429d4c073f7c/Article%205%2C%20image%203%20v4.png?raw=true"
      alt="Hypothesis Image 3"
      style="width: 100%; height: auto; display: block; cursor: pointer; border-radius: 0; transition: filter 0.3s ease;"
      class="zoomable"
    />
    <div class="plus">+</div>
  </div>

  <div class="imageBorder borderLeft">
    <img
      src="https://github.com/GabrielleDominguez/Statics-Applied-Bridging-Data-Decision-Making-in-Project-Management/blob/65156eaf56ca57c55cff72637c17429d4c073f7c/Article%205%2C%20image%204%20v4.png?raw=true"
      alt="Hypothesis Image 4"
      style="width: 100%; height: auto; display: block; cursor: pointer; border-radius: 0; transition: filter 0.3s ease;"
      class="zoomable"
    />
    <div class="plus">+</div>
  </div>
</div>

<style>
  
.imageBorder {
flex: 1; border: 1.5px solid #e2e8f0; position: relative; overflow: hidden;
}

.borderLeft {
border-left: none;
}

.plus {
position: absolute; top: 6px; right: 6px; font-size: 16px; color: rgba(0,0,0,0.4); pointer-events:none;
}
  
  /* Desktop: double size from 250px to ~500px */
  @media (min-width: 769px) {
    div[style*="flex: 1"] {
      min-width: 500px;
    }
    div[style*="flex: 1"]:hover img.zoomable {
      filter: brightness(0.85);
      transition: filter 0.3s ease;
    }
    div[style*="flex: 1"]:hover {
      box-shadow: none;
      filter: none;
      z-index: 10;
      transition: none;
    }
  }

  /* Mobile: keep exactly as is, side by side */
  @media (max-width: 768px) {
    div[style*="flex: 1"] {
      min-width: 45vw;
    }
  }

  /* Remove right border on last box */
  div[style*="flex: 1"]:last-child {
    border-right: none !important;
  }
  
  @media (hover: hover) and (pointer: fine) {
  .imageBorder:hover img.zoomable {
    filter: brightness(0.9);
    transition: filter 0.3s ease;
  }

  .imageBorder:hover .plus {
    color: rgba(0, 0, 0, 0.7);
    transition: color 0.3s ease;
  }
}
</style>

<script>
  // Modal Zoom script unchanged
  const zoomables = document.querySelectorAll('.zoomable');
  const modal = document.createElement('div');
  modal.id = 'modal';
  modal.style.cssText = `
    display:none; 
    position:fixed; 
    z-index:1000; 
    top:0; left:0; 
    width:100vw; height:100vh; 
    background:rgba(0,0,0,0.8); 
    justify-content:center; 
    align-items:center;
  `;
  modal.innerHTML = `
    <span id="modal-close" style="position: fixed; top: 20px; right: 30px; color: white; font-size: 30px; font-weight: bold; cursor: pointer;">&times;</span>
    <img id="modal-img" src="" alt="" style="max-width: 90%; max-height: 90%; border-radius: 8px; box-shadow: 0 0 15px rgba(0,0,0,0.5);" />
  `;
  document.body.appendChild(modal);

  const modalImg = document.getElementById('modal-img');
  const modalClose = document.getElementById('modal-close');

  zoomables.forEach(img => {
    img.addEventListener('click', () => {
      modal.style.display = 'flex';
      modalImg.src = img.src;
      modalImg.alt = img.alt;
    });
  });

  modalClose.addEventListener('click', () => {
    modal.style.display = 'none';
    modalImg.src = '';
  });

  modal.addEventListener('click', e => {
    if (e.target === modal) {
      modal.style.display = 'none';
      modalImg.src = '';
    }
  });

  document.addEventListener('keydown', e => {
    if (e.key === 'Escape') {
      modal.style.display = 'none';
      modalImg.src = '';
    }
  });

function generateOpenGraphTags() {
    const currentURL = window.location.href;
    
    const titleElement = document.querySelector('h1');
    const title = titleElement ? titleElement.textContent.trim() : '';
    
    const imageElement = document.querySelector('img');
    let imageURL = '';
    if (imageElement) {
      imageURL = imageElement.src;
      if (imageURL.startsWith('/')) {
        imageURL = window.location.origin + imageURL;
      }
    }
    
    const paragraphs = document.querySelectorAll('p');
    let description = '';
    for (let p of paragraphs) {
      if (p.textContent.trim() && p.textContent.trim().length > 20) {
        description = p.textContent.trim();
        if (description.length > 160) {
          description = description.substring(0, 157) + '...';
        }
        break;
      }
    }
    
    function updateMetaTag(property, content, attribute = 'property') {
      if (!content) return;
      let metaTag = document.querySelector(`meta[${attribute}="${property}"]`);
      if (!metaTag) {
        metaTag = document.createElement('meta');
        metaTag.setAttribute(attribute, property);
        document.head.appendChild(metaTag);
      }
      metaTag.setAttribute('content', content);
    }
    
    updateMetaTag('og:title', title);
    updateMetaTag('og:description', description);
    updateMetaTag('og:image', imageURL);
    updateMetaTag('og:url', currentURL);
    updateMetaTag('twitter:title', title);
    updateMetaTag('twitter:description', description);
    updateMetaTag('twitter:image', imageURL);
    
    if (title) document.title = title;
  }

  document.addEventListener('DOMContentLoaded', function() {
    setTimeout(generateOpenGraphTags, 100);
  });
</script>

---
 
## References

Triola, M. F. (2022). *Elementary statistics* (13th ed.). Pearson.  
Pearson Education. (2022). *Elementary statistics* course materials.

---

[← Back to Home](https://gabrielledominguez.github.io/Statistics-Applied-Bridging-Data-Decision-Making-in-Project-Management/)


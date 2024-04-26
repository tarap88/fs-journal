# Managing the Fullstack Application

1. Describe the two ways to bind Data in Vue?

  > | V-Model and V-Bind, One Way Binding, Two Way Binding |
  <!-- V-Model: Imagine it as a bridge: when someone types into a form field, whatever they type appears on the bridge, and the bridge delivers it straight to your Vue component's memory. Similarly, if your component's memory changes, the bridge carries that change back to the form field, so it always shows the latest information. -->

  <!-- V-Bind:It's like a way of telling Vue, "Hey, keep an eye on this thing and update it if something changes." You use it to connect bits of your component's data to parts of your HTML, like making sure that a link's address is always correct, or that an image always shows the right picture. It's like setting up a rule that says, "Whenever this data changes, make sure this part of the webpage changes too." And you can use a shorter version of it, just putting a colon (:) before the attribute you want to bind. -->

2. The `SPA` acronym stands for what?

  > | Single Page Application. |

3. What are some of the advantages/uses of a `SPA` over a traditional one?

  > | Faster User Experience, Responsive Design  |
  <!-- Faster User Experience: Imagine you're reading a book and you have to turn the page every time you want to read the next sentence. That's how traditional websites work - every time you click a link, the whole page refreshes, just like turning the page. But with Single Page Applications (SPAs), it's like having a magic book where the next sentence appears instantly without flipping the page. SPAs load everything you need once, and then they only fetch the new stuff from the server when you need it. So, it feels smoother and faster because you don't have to wait for the whole page to reload every time.

  <!-- Responsive Design: Have you ever opened a website on your phone and it looks all squished up and hard to read? That's because some websites aren't designed to fit on smaller screens. But SPAs are like chameleons - they can change their shape to fit any screen size or type of device, whether it's a big computer screen or a tiny smartphone. And the best part is, they can do this without needing a separate set of instructions for each type of device. So, it's easier for developers to make sure their websites look good and work well no matter what device you're using. --> 

4. What does the `onMounted` method in Vue do?

  > | Registers a callback to be called after the component has been mounted.|

5. What is the `v-model` attribute in Vue for, and when might you use it?

  > | V-model is used for binding data that you have defined and it is commonly used in forms and inputs. |

6. What is the package.json file used for?

  > | Metadata, Dependencies Management,and Configuration is just some ways it's used.
  In simple terms, the package.json file acts like a project manager, keeping everything in order, making sure all the necessary parts are there, and helping you share your work with others. It is a crucial component in a Node.js project

7. Which Vue attributes(directives) could you use to conditionally render elements on a page?

  > | v-text, v-html, v-model, v-bind, v-for, or v-if |

8. What is the purpose of the `key` attribute when using `v-for` on an element?

  > | The key attribute is used with the v-for so that Vue can tell the elements apart properly. |

9. What is the `<slot>` element and what is it used for?

  > | The <slot> element is a feature in Vue.js that allows you to define placeholders in your component's template where content can be injected from the parent component. We did this using ModalWrapper|

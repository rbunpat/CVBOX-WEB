<template>
    <div class="item">
      <div class="details">
        <h1>
          <slot name="contactus"></slot>
        </h1>
        <h2>
          <slot name="emailhead"></slot>
        </h2>
        <h3>
          <slot name="email"></slot>
        </h3>
      </div>
    </div>
  </template>
  
  <style scoped>
  .item {
    margin-top: 2rem;
    display: flex;
  }
  
  .details {
    flex: 1;
    margin-left: 1rem;
  }
  
  i {
    display: flex;
    place-items: center;
    place-content: center;
    width: 32px;
    height: 32px;
  
    color: var(--color-text);
  }
  h1 {
    text-align: center;
    font-size: 2rem;
    font-weight: 500;
    margin: 0;
    margin-bottom: 0.5rem;
    color: var(--color-heading);
  }
  /* h1 {
    font-size: 2rem;
    font-weight: 500;
    margin-bottom: 0.4rem;
    color: var(--color-heading);
  } */

  h2 {
    text-align: center;
    font-size: 1.5rem;
    font-weight: 500;
    margin: 0;
    margin-bottom: 0.4rem;
    color: var(--color-text);
    /* font-size: 1.5rem;
    font-weight: 500;
    margin-bottom: 0.4rem;
    color: var(--color-heading); */
  }
  
  h3 {
    text-align: center;
    font-size: 1.2rem;
    font-weight: 500;
    margin-bottom: 0.4rem;
    color: var(--color-text);
  }
  
  @media (min-width: 1024px) {
    .item {
      margin-top: 0;
      padding: 0.4rem 0 1rem calc(var(--section-gap) / 2);
    }
  
    i {
      top: calc(50% - 25px);
      left: -26px;
      position: absolute;
      border: 1px solid var(--color-border);
      background: var(--color-background);
      border-radius: 8px;
      width: 50px;
      height: 50px;
    }
  
    .item:before {
      content: ' ';
      border-left: 1px solid var(--color-border);
      position: absolute;
      left: 0;
      bottom: calc(50% + 25px);
      height: calc(50% - 25px);
    }
  
    .item:after {
      content: ' ';
      border-left: 1px solid var(--color-border);
      position: absolute;
      left: 0;
      top: calc(50% + 25px);
      height: calc(50% - 25px);
    }
  
    .item:first-of-type:before {
      display: none;
    }
  
    .item:last-of-type:after {
      display: none;
    }
  }
  </style>
  
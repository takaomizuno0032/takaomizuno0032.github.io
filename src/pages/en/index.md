---
title: Takao Mizuno - Research Engineer
description: Research Engineer interested in security, data privacy, and blockchain technology.
layout: ../../layouts/Layout.astro
---

<style is:global>
	.hobby-images {
		display: flex;
		gap: 1.5rem;
		margin: 1.5rem 0;
		flex-wrap: wrap;
	}

	.image-wrapper {
		position: relative;
		display: inline-block;
		max-width: 300px;
	}

	.hobby-images img {
		max-width: 300px;
		width: 100%;
		height: auto;
		object-fit: contain;
		border-radius: 4px;
		box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
		transition: transform 0.3s ease, box-shadow 0.3s ease, filter 0.3s ease;
		display: block;
	}

	.image-wrapper:hover img {
		transform: translateY(-4px);
		box-shadow: 0 8px 24px rgba(0, 0, 0, 0.15);
		filter: brightness(0.95);
	}

	.image-popup {
		position: absolute;
		bottom: 0;
		left: 0;
		right: 0;
		background: rgba(0, 0, 0, 0.85);
		backdrop-filter: blur(10px);
		color: #fff;
		padding: 1.5rem;
		border-radius: 0 0 4px 4px;
		opacity: 0;
		transform: translateY(10px);
		transition: opacity 0.3s ease, transform 0.3s ease;
		pointer-events: none;
		font-size: 0.9rem;
		line-height: 1.6;
	}

	.image-wrapper:hover .image-popup {
		opacity: 1;
		transform: translateY(0);
	}

	.image-popup p {
		margin: 0;
		color: #fff;
	}

	@media (max-width: 640px) {
		.hobby-images {
			flex-direction: column;
		}

		.image-wrapper {
			max-width: 100%;
		}

		.hobby-images img {
			max-width: 100%;
		}
	}
</style>

# Takao Mizuno

## About Me

I believe my purpose is to contribute to making society better through technology. I am interested in security, data privacy, and blockchain.

## Education

- **2024**, M.S. in Information Technology at The University of Queensland
  Lab: UQ Cyber (Nominated in one of the best master thesis)
- **2020**, Bachelor in Education at The University of Tokyo

## Work Experience

- **2022~Current**, Freelance Engineer
  - Ex.
    - Gaiax, Inc., Research Engineer
    - PeopleX Inc., AI Engineer
    - Preferred Networks Inc., Research Engineer
- **2024~2025**, Secure Vertex Inc., Chief Technology Officer
- **2020~2022**, Amiya, Inc., Software Engineer

## Hobbies

Wine and Coffee

<div class="hobby-images">
  <div class="image-wrapper">
    <img src="/index/wine.jpg" alt="Wine" />
    <div class="image-popup">
      <p>A winery I visited in Australia, where I lived for three years</p>
    </div>
  </div>
</div>

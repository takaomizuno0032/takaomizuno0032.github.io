---
title: Blogs
description: Blog posts and articles
layout: ../layouts/Layout.astro
---

<style is:global>
	.blogs-container {
		margin: 2rem 0;
	}

	.blogs-grid {
		display: grid;
		grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
		gap: 2rem;
		margin-top: 2rem;
	}

	.blog-card {
		background: #fff;
		border-radius: 8px;
		overflow: hidden;
		box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
		transition: transform 0.2s ease, box-shadow 0.2s ease;
		text-decoration: none;
		color: inherit;
		display: block;
	}

	.blog-card:hover {
		transform: translateY(-4px);
		box-shadow: 0 4px 16px rgba(0, 0, 0, 0.15);
	}

	.blog-image {
		width: 100%;
		height: 200px;
		object-fit: cover;
		display: block;
	}

	.blog-content {
		padding: 1.5rem;
	}

	.blog-category {
		display: inline-block;
		background: #f0f0f0;
		color: #666;
		font-size: 0.85rem;
		padding: 0.25rem 0.75rem;
		border-radius: 4px;
		margin-bottom: 0.75rem;
	}

	.blog-title {
		font-size: 1.1rem;
		font-weight: 600;
		margin: 0 0 0.75rem 0;
		color: #000;
		line-height: 1.4;
	}

	.blog-description {
		font-size: 0.9rem;
		color: #666;
		line-height: 1.6;
		margin: 0 0 1rem 0;
		display: -webkit-box;
		-webkit-line-clamp: 3;
		-webkit-box-orient: vertical;
		overflow: hidden;
	}

	.blog-date {
		font-size: 0.85rem;
		color: #999;
		margin: 0;
	}

	@media (max-width: 768px) {
		.blogs-grid {
			grid-template-columns: 1fr;
			gap: 1.5rem;
		}
	}
</style>

# Blogs

<div class="blogs-container">
	<p>Coming Soon...</p>
</div>


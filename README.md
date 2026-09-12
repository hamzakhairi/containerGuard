# containerGuard
containerGuard is a DevOps platform that scans Dockerfiles and docker images for security vulnerabilities and beast-practice issues. it uses automated scanning tools, generates reports

# basic folder architecture 
frontend/       -> Next.js dashboard.
backend/        -> REST API.
scanner-worker/ -> Trivy + Hadolint + Dockle + Grype.
report-service/ -> Generate/store scan reports.
redis/          -> Job queue.
postgres/       -> Users + scans + reports.
nginx/          -> Reverse proxy.
monitoring/     -> Prometheus + Grafana.




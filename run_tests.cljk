(require '[clojure.test :as t] 'okaimono.methods.test-agent
         'okaimono.kotoba.test-ingest-internal 'okaimono.repository-contract-test)
(let [r (t/run-tests 'okaimono.methods.test-agent
                     'okaimono.kotoba.test-ingest-internal
                     'okaimono.repository-contract-test)]
  (System/exit (if (zero? (+ (:fail r) (:error r))) 0 1)))
